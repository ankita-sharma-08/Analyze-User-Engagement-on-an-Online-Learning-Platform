# Analyze-User-Engagement-on-an-Online-Learning-Platform

## 📌 Project Overview

This project focuses on analyzing user engagement and learning activity on an online learning platform. The objective is to explore student behavior, evaluate course completion rates, understand feedback and satisfaction levels, and identify engagement patterns across courses and student demographics.

Using Python and data visualization libraries, this project performs data cleaning, exploratory data analysis (EDA), statistical analysis, and visualization to derive meaningful insights from student activity, feedback, and demographic data.

## 🎯 Project Objectives

- Analyze the overall average course completion rate.
- Identify courses with the highest and lowest average engagement time.
- Understand student engagement across different age groups and locations.
- Calculate average feedback ratings for each course.
- Explore the relationship between course completion rates and feedback ratings.
- Identify students with high engagement and satisfaction levels.
- Visualize feedback ratings, time spent learning, and course completion trends.
- Compare student feedback by age and gender.

## 🛠️ Technologies Used

- **Python** – Data analysis and processing
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Jupyter Notebook** – Interactive analysis and documentation

**Note:** The three CSV files are required to run the notebook. Add them to your repository alongside the notebook.

## 📁 Datasets Description

The project uses three datasets:

### 1. `course_activity.csv`

Contains information about student activity and course progress.

Key columns used:
- `Student_ID`
- `Course_ID`
- `Date`
- `Time_Spent_Minutes`
- `Completion_Percentage`

### 2. `feedback.csv`

Contains student feedback and course ratings.

Key columns used:
- `Student_ID`
- `Course_ID`
- `Rating`

### 3. `students.csv`

Contains student demographic information.

Key columns used:
- `Student_ID`
- `Age`
- `Gender`
- `Location`

## 🔍 Project Workflow

### 1. Data Loading
- Imported the required Python libraries.
- Loaded the three CSV datasets using Pandas.
- Examined the first few rows of each dataset.

### 2. Data Exploration and Cleaning
- Inspected dataset structures and data types.
- Checked for missing values.
- Identified duplicate records.
- Generated descriptive statistics.
- Converted the `Date` column into a datetime format.

### 3. Exploratory Data Analysis (EDA)
- Calculated the overall average completion percentage.
- Compared average engagement time across courses.
- Analyzed engagement by age and location.
- Calculated average feedback ratings by course.
- Explored the correlation between completion percentage and feedback ratings.
- Identified students with the highest total engagement time and average satisfaction ratings.

### 4. Data Visualization
Created visualizations to understand student behavior and course performance, including:

- Distribution of feedback ratings.
- Distribution of time spent on courses.
- Engagement patterns across courses over time.
- Feedback ratings by age.
- Comparison of feedback ratings across courses.
- Feedback rating distribution by gender.
- Course completion trends over time.

### 5. Data Integration
Merged course activity, feedback, and student demographic information where needed to support a more comprehensive analysis.

## 📈 Key Business Questions

This project investigates the following questions:

1. What is the overall average course completion rate?
2. Which courses have the highest and lowest average engagement time?
3. How does student engagement vary by age and location?
4. What is the average feedback rating for each course?
5. Is there a correlation between completion percentage and feedback ratings?
6. Which students demonstrate the highest engagement and satisfaction?
7. How are feedback ratings distributed across students?
8. Do feedback ratings vary by age, gender, or course?
9. How do engagement and course completion change over time?

## 💡 Business Value

The analysis can help an online learning platform:

- **Improve course design:** Identify courses with comparatively low engagement.
- **Increase completion rates:** Understand course progress and completion patterns.
- **Enhance student satisfaction:** Evaluate feedback ratings across courses.
- **Personalize learning experiences:** Explore engagement differences across student demographics.
- **Monitor performance:** Track engagement and completion trends over time.
- **Support data-driven decisions:** Use measurable indicators to guide improvements in the learning experience.

## ⚙️ Installation and Setup

### Prerequisites

Install Python 3 and Jupyter Notebook or JupyterLab.

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
```

### Step 2: Navigate to the Project Folder

```bash
cd YOUR-REPOSITORY-NAME
```

### Step 3: Install Required Libraries

```bash
pip install pandas matplotlib seaborn jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the Analysis

Open `Data_Analyst_Intern_Assignment.ipynb` and execute the notebook cells sequentially.

Ensure that `course_activity.csv`, `feedback.csv`, and `students.csv` are located in the working directory used by the notebook.

## 📊 Results and Insights

The notebook calculates course completion rates, compares engagement across courses, examines demographic differences, analyzes feedback ratings, and generates visualizations of learning activity over time.


