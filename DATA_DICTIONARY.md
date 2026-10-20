# 📖 Data Dictionary

Explains every column in [`data/Cleaned_Student_Data.csv`](data/Cleaned_Student_Data.csv).

**1,539 rows (one per student) · 15 columns · no missing values**

| Column | Type | Description | Values / Range |
|---|---|---|---|
| `student_id` | Text | Unique ID for each student | e.g. S007 |
| `age` | Whole number | Student's age in years | 18 – 25 |
| `gender` | Text | Student's gender | Male, Female, Other |
| `major` | Text | Field of study | Arts, Business, Computer Science, Engineering |
| `GPA` | Decimal | Grade point average | 2.0 – 4.0 |
| `course_load` | Whole number | Number of courses the student is taking | up to 6 |
| `avg_course_grade` | Decimal | Average grade across courses (%) | up to 100 |
| `attendance_rate` | Decimal | Share of classes attended | 0 – 1 (0.79 = 79%) |
| `enrollment_status` | Text | Current enrollment state | Active, Graduated, Leave |
| `lms_logins_past_month` | Whole number | Times the student logged into the learning platform last month | 0 – 39 |
| `avg_session_duration_minutes` | Whole number | Average length of each LMS session, in minutes | up to 89 |
| `assignment_submission_rate` | Decimal | Share of assignments submitted | 0 – 1 |
| `forum_participation_count` | Whole number | Number of discussion forum activities | 0 – 19 |
| `video_completion_rate` | Decimal | Share of lecture videos watched to the end | 0 – 1 |
| `risk_level` | Text | Academic risk category of the student | High, Medium, Low |

## Category Breakdown

| Column | Counts |
|---|---|
| `risk_level` | High 803 · Medium 452 · Low 284 |
| `major` | Arts 401 · Computer Science 388 · Engineering 383 · Business 367 |
| `gender` | Male 531 · Female 522 · Other 486 |
| `enrollment_status` | Active 538 · Graduated 509 · Leave 492 |
