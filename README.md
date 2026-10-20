<div align="center">

# 🎓 Student Performance & Risk Dashboard

### An interactive Power BI dashboard that shows which students are at risk, and what really separates them from the rest.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-0078D4?style=for-the-badge)
![Students](https://img.shields.io/badge/Students-1%2C539-2ea44f?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Education%20Analytics-8957e5?style=for-the-badge)

<br>

![Dashboard Preview](screenshots/dashboard-overview.png)

</div>

---

## 📖 About the Project

Universities collect a lot of data on their students, but it is rarely in one place. This project combines **academic results, class attendance, and online learning (LMS) activity** for **1,539 students** into a single, easy-to-read dashboard.

The goal is simple: help an advisor or analyst see **who is at risk, how they differ from other students, and which behaviours matter most.**

---

## 🎯 Questions This Dashboard Answers

| # | Question |
|---|---|
| 1 | How is the student cohort performing overall? |
| 2 | How does GPA differ between **High, Medium and Low risk** students? |
| 3 | Is attendance linked to academic performance? |
| 4 | Do at-risk students use the learning platform differently? |
| 5 | Does performance change from one major to another? |

---

## 📊 Headline Numbers

<div align="center">

| 🎯 Average GPA | 📅 Average Attendance | 📝 Submission Rate | 💻 Avg. LMS Logins / Month |
|:---:|:---:|:---:|:---:|
| **3.01** | **79%** | **75%** | **19.3** |

</div>

---

## 🔍 Key Insights

### 1️⃣ Risk level lines up closely with GPA
| Risk Level | Students | Avg GPA |
|---|:---:|:---:|
| 🔴 High | 803 | **2.80** |
| 🟠 Medium | 452 | **3.11** |
| 🟢 Low | 284 | **3.46** |

Low-risk students average **0.66 GPA points higher** than high-risk students.

### 2️⃣ Attendance is the clearest dividing line
| Risk Level | Avg Attendance |
|---|:---:|
| 🔴 High | **73%** |
| 🟠 Medium | **83%** |
| 🟢 Low | **92%** |

A **19-point attendance gap** separates high-risk from low-risk students. No other behaviour in the data shows a gap this large.

### 3️⃣ Online activity looks the same for every group
Logins per month (~19), assignment submission (~75%) and video completion (~75%) are almost identical across risk levels. At-risk students are not less active online, so **showing up in class matters more than logging in.**

### 4️⃣ Major doesn't decide success
Average GPA sits between **2.99 and 3.05** for Arts, Business, Engineering and Computer Science, so risk is a student-level issue rather than a department-level one.

### 5️⃣ More than half the cohort is flagged High risk
**52%** of students (803 of 1,539) fall into the High risk group.

---

## 🖥️ Dashboard Walkthrough

| Visual | What it shows |
|---|---|
| **KPI Cards** | Average GPA, attendance, submission rate and LMS logins at a glance |
| **Average GPA by Risk Level** | Column chart comparing GPA across High, Medium and Low risk |
| **Average LMS Logins by Risk Level** | Donut chart of monthly platform activity per risk group |
| **Attendance vs GPA** | Area chart with trend line exploring how attendance relates to GPA |
| **Engagement Trends** | Assignment submission rate split by risk level |
| **GPA by Major** | Bar chart comparing performance across the four majors |
| **Risk Level Filter** | Slicer that updates the whole page for any risk group |

---

## 🗂️ Dataset

**1,539 students · 15 columns · no missing values · one row per student**

| Category | Columns |
|---|---|
| **Student profile** | `student_id`, `age`, `gender`, `major`, `enrollment_status` |
| **Academic performance** | `GPA`, `avg_course_grade`, `course_load` |
| **Attendance** | `attendance_rate` |
| **Online learning (LMS)** | `lms_logins_past_month`, `avg_session_duration_minutes`, `assignment_submission_rate`, `forum_participation_count`, `video_completion_rate` |
| **Target label** | `risk_level` (High / Medium / Low) |

| Breakdown | Count |
|---|---|
| **Majors** | Arts 401 · Computer Science 388 · Engineering 383 · Business 367 |
| **Enrollment** | Active 538 · Graduated 509 · Leave 492 |
| **Gender** | Male 531 · Female 522 · Other 486 |

> Rates such as attendance and submission are stored as decimals between 0 and 1 (0.79 = 79%).

---

## 🧰 Tech & Skills

- **Power BI Desktop**: data modelling, interactive visuals, slicers, custom dark theme
- **DAX**: calculated measures for KPIs
- **Data Cleaning**: prepared dataset (`Cleaned_Student_Data.csv`)
- **Data Storytelling**: turning raw numbers into clear, actionable insights

---

## ▶️ Run It Yourself

1. **Download** this repository (green **Code** button → **Download ZIP**)
2. Open `report/Student_Performance_Dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. If Power BI asks for the data, go to **Home → Transform data → Data source settings → Change Source** and select `data/Cleaned_Student_Data.csv`
4. Click the **Risk Level** filter to explore each group

---

## 👤 Author

**Madhavi Kapoor**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/madhavi-kapoor-a2a3a4377/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Madhavi-Kapoor)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:madhavikapoor2006@example.com)

<div align="center">

⭐ **If you like this project, give it a star!** ⭐

</div>
