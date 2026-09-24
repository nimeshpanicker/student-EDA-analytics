# 🎓 Student Performance Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Analysis-green)
![Education Analytics](https://img.shields.io/badge/Education-Analytics-blue)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Portfolio-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

> An interactive Power BI and Excel analytics project analysing student
> academic performance, test preparation, demographics, study habits,
> assignment completion, screen time, and performance levels.

---

# 📌 Project Overview

This project analyses student academic performance using two complementary
datasets and Power BI dashboards.

The core analysis contains a **100-student score dataset** covering
Mathematics, Reading, Writing, Gender, Ethnicity, Parental Education, and
Test Preparation.

A separate **300-student study-habit dataset** provides an exploratory view
of Study Hours, Sleep Hours, Screen Time, Assignment Completion, Practice
Score, and Performance Level.

The project combines Microsoft Excel and Power BI to transform student-level
data into interactive dashboards, KPIs, comparative analysis, and
actionable academic insights.

---

# 🎯 Project Objectives

The main objectives of this project are:

- Analyse overall academic performance across the student cohort.
- Monitor Mathematics, Reading, Writing, and overall score performance.
- Compare academic performance across gender and ethnicity groups.
- Analyse performance by parental education background.
- Measure the relationship between test preparation and academic scores.
- Identify the highest and lowest-performing students.
- Analyse score distribution across performance bands.
- Examine study hours, sleep hours, screen time, and assignment completion.
- Compare behavioral patterns across Low, Medium, and High performance levels.
- Build interactive Power BI dashboards for self-service analysis.
- Translate findings into practical academic recommendations.

---

# 📊 Dataset

## Core Student Score Dataset

| Dataset Attribute | Details |
|---|---|
| Student Count | **100** |
| Number of Columns | **8** |
| Granularity | **One row per student** |
| Student ID | **S001–S100** |
| Gender | **Male / Female** |
| Ethnicity | **Group A–E** |
| Parental Education | **6 categories** |
| Test Preparation | **Completed / None** |
| Math Score | **0–100** |
| Reading Score | **0–100** |
| Writing Score | **0–100** |

The overall Score Percentage is calculated as the average of the
Mathematics, Reading, and Writing scores.

---

## Companion Study-Habit Dataset

| Dataset Attribute | Details |
|---|---|
| Student Count | **300** |
| Study Hours | Included |
| Sleep Hours | Included |
| Screen Time | Included |
| Assignments Completed | Included |
| Practice Score | Included |
| Performance Level | **Low / Medium / High** |

> The 300-student study-habit dataset is a separate cohort from the
> 100-student academic score dataset. The two datasets support related but
> distinct analyses.

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data organization, review and preparation |
| **Power BI** | Interactive dashboard development |
| **Power BI Visuals** | KPI cards, bar charts, donut charts, scatter plots |
| **Data Analysis** | Performance comparison and behavioral analysis |
| **Exploratory Data Analysis** | Study-habit and performance-level analysis |
| **Data Storytelling** | Translating analysis into academic insights |

---

# 📈 Dashboard

## Student Performance Dashboard

The core Power BI dashboard contains:

- Student Count KPI
- Average Reading Score KPI
- Average Writing Score KPI
- Average Maths Score KPI
- Average Score Percentage KPI
- Average Score Percentage by Ethnicity
- Average Score Percentage by Gender
- Sum of Score Percentage by Parental Education
- Average Score Percentage by Test Preparation
- Ethnicity and Parental Education analysis
- Top-performing students
- Interactive slicers for:
  - Ethnicity
  - Gender
  - Parental Education
  - Test Preparation

---

## Student Performance Classification — EDA Dashboard

The companion dashboard analyses:

- Student Count
- Average Study Hours
- Average Sleep Hours
- Average Screen Time
- Average Practice Score
- Study Hours by Performance Level
- Screen Time by Performance Level
- Sleep Hours by Performance Level
- Assignment Completion by Performance Level
- Study Hours and Assignment Completion
- Screen Time and Practice Score
- Performance Level classification

---

# 📊 Key Performance Indicators

## Core Student Performance Dashboard

| KPI | Result |
|---|---:|
| Student Count | **100** |
| Average Reading Score | **60.49** |
| Average Writing Score | **60.53** |
| Average Maths Score | **62.51** |
| Average Score Percentage | **61.18** |

---

## Companion Study-Habit Dashboard

| KPI | Result |
|---|---:|
| Student Count | **300** |
| Average Study Hours | **5.06** |
| Average Sleep Hours | **7.59** |
| Average Screen Time | **4.32** |
| Average Practice Score | **68.21** |

---

# 📈 Key Findings

## 📚 Subject-Level Performance

| Subject | Average Score |
|---|---:|
| Mathematics | **62.51** |
| Writing | **60.53** |
| Reading | **60.49** |

Mathematics is the strongest subject in the 100-student cohort, while
Reading has the lowest average score.

The differences between subjects are relatively small, but the analysis
shows that subject scores are only weakly correlated.

---

## 👥 Performance by Gender

| Gender | Students | Average Score % |
|---|---:|---:|
| Female | **53** | **61.26%** |
| Male | **47** | **61.08%** |

The overall difference between female and male students is only
**0.18 percentage points**.

This indicates that gender is not a meaningful differentiator of overall
performance within this dataset.

---

## 🌎 Performance by Ethnicity

| Ethnicity | Students | Average Score % |
|---|---:|---:|
| Group A | **26** | **63.03** |
| Group D | **17** | **61.63** |
| Group B | **14** | **60.60** |
| Group E | **19** | **60.11** |
| Group C | **24** | **60.04** |

Group A records the highest average score at **63.03**, while Group C records
the lowest at **60.04**.

The overall spread across the five groups is less than three points.

---

## 🎓 Parental Education Analysis

| Parental Education | Students | Average Score % |
|---|---:|---:|
| Some College | **13** | **63.31** |
| Bachelor's Degree | **17** | **63.12** |
| High School | **20** | **61.67** |
| Some High School | **14** | **60.74** |
| Associate's Degree | **23** | **59.51** |
| Master's Degree | **13** | **59.18** |

The relationship between parental education and student performance is
not linear in this dataset.

The Master's Degree group has the lowest average score, but this group
contains only 13 students, so the result should not be treated as evidence
of a broader relationship without a larger sample.

---

# 📚 Test Preparation Analysis

| Subject | Completed Prep | No Prep | Gap |
|---|---:|---:|---:|
| Mathematics | **68.34** | **58.46** | **+9.88** |
| Reading | **64.61** | **57.63** | **+6.98** |
| Writing | **66.07** | **56.68** | **+9.40** |
| Overall | **66.34** | **57.59** | **+8.75** |

Test preparation shows the largest observed performance difference in the
core dataset.

Only **41 students** completed test preparation, while **59 students**
did not.

The completed-preparation group has an **8.75-point higher overall average
score** than the group with no preparation.

> These results describe an association in the dataset and should not be
> interpreted as proof that test preparation alone causes the score
> difference.

---

# 🏆 Top Performing Students

| Rank | Student ID | Avg. Score % | Ethnicity | Parental Education | Test Prep |
|---|---|---:|---|---|---|
| 1 | **S011** | **78.00** | Group C | High School | Completed |
| 2 | **S070** | **77.67** | Group D | Master's Degree | Completed |
| 3 | **S044** | **76.00** | Group A | Bachelor's Degree | Completed |
| 4 | **S069** | **75.33** | Group A | Bachelor's Degree | Completed |
| 5 | **S098** | **75.00** | Group A | Associate's Degree | Completed |

All five top-performing students completed test preparation.

---

# 📉 Score Distribution

| Score Band | Number of Students |
|---|---:|
| Below 50% | **10** |
| 50% – 60% | **28** |
| 60% – 70% | **50** |
| 70% – 80% | **12** |
| 80%+ | **0** |

Half of the students fall within the **60–70%** score range.

No student in the core dataset achieved a score of 80% or above.

---

# 📖 Study-Habit & Performance Analysis

The companion 300-student dataset classifies students into Low, Medium,
and High performance levels.

| Performance Level | Avg. Study Hours | Avg. Sleep Hours | Avg. Screen Time | Assignments Completed |
|---|---:|---:|---:|---:|
| High | **7.5** | **7.7** | **2.24** | **937** |
| Medium | **5.0** | **7.7** | **4.25** | **607** |
| Low | **2.7** | **7.3** | **6.49** | **260** |

### Study Hours

High performers average **7.5 study hours**, compared with **2.7 hours**
for Low performers.

### Screen Time

Low performers report **6.49 hours** of screen time compared with
**2.24 hours** for High performers.

### Assignment Completion

High performers complete **937 assignments**, compared with **260** among
Low performers.

### Sleep

Average sleep remains relatively similar across performance levels,
ranging from **7.3 to 7.7 hours**.

---

# 💡 Key Insights

## 1. Test Preparation Shows the Largest Performance Difference

Students who completed test preparation recorded an overall average score
of **66.34**, compared with **57.59** among students who did not.

The resulting **8.75-point gap** is larger than the demographic differences
observed in the core dataset.

---

## 2. The Majority of Students Are in the Middle Performance Band

**50 out of 100 students** fall within the 60–70% score range.

This creates a substantial middle-performing group that could be monitored
through academic support and preparation programs.

---

## 3. Mathematics Is the Strongest Subject

Mathematics has an average score of **62.51**, compared with **60.53 in
Writing** and **60.49 in Reading**.

This suggests that academic support should consider subject-specific needs
rather than relying only on an overall score.

---

## 4. Gender Differences Are Minimal

Female students average **61.26%**, while male students average **61.08%**.

The difference is only **0.18 points**.

---

## 5. Study Time Is Associated With Performance Level

High performers average **7.5 study hours**, while Low performers average
**2.7 hours**.

This represents a substantial difference in reported study time across
performance levels.

---

## 6. Screen Time Shows an Inverse Pattern

Low performers report **6.49 hours** of screen time compared with
**2.24 hours** among High performers.

---

## 7. Assignment Completion Is a Strong Differentiator

High performers complete **937 assignments**, compared with **260** among
Low performers.

Assignment completion can therefore be considered as a potential
early-warning metric for further academic analysis.

---

# 📋 Recommendations

## 📚 Expand Test Preparation Access

Increase awareness and access to test-preparation resources, particularly
because 59% of students in the core dataset had not completed preparation.

---

## 📝 Monitor Assignment Completion

Use assignment-completion tracking as an early-warning indicator to identify
students who may require academic support.

---

## 📖 Provide Subject-Specific Support

Focus additional support on Reading and Writing rather than relying only
on the overall score because subject-level performance can vary between
students.

---

## 🎯 Support the 60–70% Student Group

Monitor the large middle-performing group and evaluate whether structured
preparation and tutoring programs improve their performance.

---

## ⏱️ Encourage Structured Study Habits

Encourage consistent study schedules and monitor study-time patterns as
part of academic support programs.

---

## 📱 Promote Screen-Time Awareness

The companion dataset shows substantially higher screen time among Low
performers. Further analysis can investigate whether this pattern remains
consistent across larger student cohorts.

---

## ⚠️ Use Demographic Factors Carefully

Gender and ethnicity show relatively small performance differences in this
dataset.

Parental education also shows a non-linear pattern and small group sizes.

Therefore, demographic variables should not be used as the primary basis
for targeting academic interventions without additional evidence.

---

# 📊 Dashboard Features

### Core Dashboard

- KPI Cards
- Ethnicity performance analysis
- Gender performance analysis
- Parental education analysis
- Test preparation analysis
- Ethnicity and parental education comparison
- Top-performing student analysis
- Interactive slicers

### EDA Dashboard

- Performance-level analysis
- Study-hours analysis
- Screen-time analysis
- Sleep-hours analysis
- Assignment-completion analysis
- Practice-score analysis
- Scatter plots
- Performance-level filtering

---

# 📁 Project Structure

```text
student-performance-analytics/
│
├── README.md
│
├── data/
│   └── student_performance_100.xlsx
│
├── dashboard/
│   └── Student_Performance_Dashboard.pdf
│
└── reports/
    └── Student_Performance_Analytics_Report.pdf
