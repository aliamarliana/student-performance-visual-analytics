# 📊 Student Performance Analysis using xAPI-Edu-Data

## 📌 Project Overview
This project analyses factors influencing student performance using the **[xAPI-Edu-Data dataset](https://www.kaggle.com/datasets/aljarah/xAPI-Edu-Data)**, which contains 480 student records with 17 attributes (demographic, behavioural, and parental engagement).  
We explored how absenteeism, parental involvement, and student engagement affect academic outcomes, and visualized findings using **Tableau** dashboards and storytelling features.


The study shows that:
- Higher **parental engagement** correlates with better academic outcomes.  
- **Absenteeism** is strongly associated with lower student performance.  
- **Student engagement metrics** (resource use, raised hands, discussions) are strong predictors of success.  

This project highlights the value of data visualization for educators and policymakers by transforming raw data into actionable insights.

---

## 🎯 Objectives
- Examine proportions of student performance across different education levels.  
- Identify the relationship between **absenteeism** and academic success.  
- Analyse the impact of **parental satisfaction and involvement**.  
- Compare **engagement metrics** across performance levels (Low, Medium, High).  

---

## 📂 Dataset
- **xAPI-Edu-Data.xlsx**  
  Contains demographic, behavioural, and engagement attributes with student performance labels (Low, Medium, High).  

Attributes include:
- Demographics (Gender, Nationality, StageID, GradeID, SectionID, Topic, Semester)  
- Parental factors (Relation, Satisfaction, Survey participation)  
- Engagement metrics (Raised Hands, Resource Visits, Announcement Views, Discussions)  
- Target variable: **Class (L, M, H)** → student performance level  

---

## 🛠️ Methods & Tools
- **Tool:** Tableau (interactive dashboards, filtering, storytelling)  
- **Visualization idioms:**  
  - 100% Stacked Bar Chart → performance by stage, gender, nationality  
  - Horizontal Bar Chart → absenteeism vs performance  
  - Side-by-Side & Stacked Bar Charts → parental satisfaction & demographics  
  - Side-by-Side Bar Chart → student engagement metrics  

---

## 📊 Tasks & Contributions
### Task 1 – Performance Levels Across Educational Stages  
Visualized proportions of student performance (High, Medium, Low) by stage, gender, nationality. *(100% stacked bar chart)*  

### Task 2 – Absenteeism vs Performance  
Analysed correlation between absence days (Under-7, Above-7) and performance categories. *(Horizontal bar chart)*  

### Task 3 – Parental Satisfaction & Involvement  
Explored relationship between parental satisfaction and student performance across demographics. *(Side-by-side & stacked bar charts)*  

### ✅ Task 4 – **Student Engagement Metrics Across Performance Levels (Contribution by Alia Marliana)**  
Designed and implemented visualization of **engagement metrics** (Announcement Views, Raised Hands, Visited Resources, Discussions) across performance levels (Low, Medium, High).  

**Key Features:**
- **Side-by-Side Bar Chart** in Tableau to compare engagement metrics across performance levels.  
- **Interactive filters** for *Topic* and *Section* allow exploration of subgroup differences.  
- **Colour encoding** for metrics to ensure clarity and comparability.  
- **Tooltips** display exact average values for deeper analysis.  

**Findings:**
- High-performing students consistently show higher **Visited Resources** and **Raised Hands** counts.  
- **Announcement Views** and **Discussions** vary less across groups.  
- Section-level filters revealed lower engagement in *Section B*.  
- Topic-level filters showed **Science** consistently had the highest engagement.  

**Reflection:**
- Side-by-side bar charts effectively compared engagement patterns.  
- Limitation: filters allow subgroup exploration, but do not compare filters directly (e.g., Section A vs Section B side-by-side).  
- Future work: add **clustered column charts** or **scatterplots** to allow more granular comparisons.  
