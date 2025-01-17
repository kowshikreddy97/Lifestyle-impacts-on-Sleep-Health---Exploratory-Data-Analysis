Introduction
-
The main objective of the project is to explore the relationship between various life style factors - such as physical activity, stress levels and occupation and their impact on sleep duration and quality. Additionally, the study aims to analyze how cardiovascular health metrics, including blood pressure and heart rate, correlate with sleep health and disorders like insomnia and sleep apnea. The goal is to uncover actionable insights that can guide individuals toward better sleep habits and help healthcare professionals identify high-risk groups for sleep disorders.

Given the growing concerns around sleep disorders, especially among college students and working professionals who often face high stress levels and irregular schedules, this dataset provides a meaningful way to investigate how daily habits can affect overall well-being

Fields: Gender, Age, Occupation, Physical activity level, stress level, BMI, sleep disorder, sleep duration, quality of sleep, BP, heart rate, daily steps.

Research Questions
-
Q1) How does the physical activity level influence sleep quality and duration?
Q2) Is there any relationship between stress levels and likelihood of having a sleep disorder?
Q3) What are the common characteristics (age, BMI, heart rate, etc.) of individuals with sleep disorders compared to those without?

Data Preprocessing and Analysis: 
-
 - Imported data and reviewed it. 
 - Checked the central tendency measures - mean median and mode etc. Univariate analysis.
 - Checked and removed outliers in the data.

  Q1) scatter plot between physical activity and sleep quality, physical activity and sleep duration.
  Ans: A positive relationship between them. 

  Q2) Box plot - stress level and sleep disorder.
  Ans: Individuals with sleep disorder have higher stress levels.

  Q3) Box plot - Age vs sleep disorder, heart_rate vs sleep disorder, daily steps vs sleep disorder.
  Ans: Individuals with sleep disorders tend to be older compared to those without. Heart rate appears slightly higher in those with sleep disorders. Individuals with sleep disorders generally take fewer daily steps.

Exploratory Data Analysis: 
-
Created a correlation heat map. It shows relationship between numerical variables 

- A weak positive correlation between physical activity and sleep quality.
- A slight negative correlation between stress levels and sleep quality.
- Heart rate shows some correlation with stress and sleep disorder metrics.

Pairwise Relationships

- The pairplot explores relationships between variables such as sleep duration, sleep quality, physical activity, stress level, heart rate, and daily steps.
- No strong linear relationships are immediately visible, though physical activity shows a modest relationship with sleep quality and duration.

Interesting Insights
-

- Physical Activity: Individuals with higher physical activity levels seem to report slightly better sleep quality and duration, though the correlation is not particularly strong.
- Stress and Sleep Disorders: Stress levels are higher among individuals with sleep disorders, particularly those with Sleep Apnea.
- Heart Rate and Sleep: Individuals with sleep disorders tend to have slightly elevated heart rates, which could be related to overall cardiovascular health.

