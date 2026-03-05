📊 Student Performance Analysis (EDA)

📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a Student Performance dataset to understand the factors affecting student scores in Math, Reading, and Writing.

The goal of this project is to practice data cleaning, statistical exploration, and visualization using Python libraries commonly used in Data Science and Machine Learning workflows.

Through various visualizations and analyses, we explore how factors such as gender, parental education level, and subject relationships influence student academic performance.

🎯 Objectives

The main objectives of this project are:
- Understand the structure and distribution of the dataset
- Identify patterns and relationships between subjects
- Analyze the impact of gender on academic performance
- Study the influence of parental education level
- Visualize score distributions and correlations
- Build a strong EDA foundation for future ML models

🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

📂 Dataset Information

The dataset contains student academic performance data with the following key features:

Feature	Description

- gender	                         Gender of the student
- race/ethnicity	                 Student ethnicity group
- parental level of education	     Education level of parents
- lunch	                             Standard or free/reduced lunch
- test preparation course	         Whether the student completed preparation course
- math score	                     Student score in mathematics
- reading score	                     Student score in reading
- writing score	                     Student score in writing

🔎 Exploratory Data Analysis

The following analyses were performed during the project.

📊 Score Distribution Across Subjects

Histograms were used to visualize the distribution of student scores.

Observations:

- Most student scores lie between 50–80
- The distributions are approximately normal
- Reading and writing scores appear slightly higher than math scores

📦 Subject Score Comparison

Boxplots were created to compare score spread across subjects.

Insights:

- Writing and reading scores show similar distributions
- Math scores show slightly larger variability
- Some outliers exist in each subject

🎓 Effect of Parental Education

Student scores were analyzed based on parental education level.

Key Insights:

- Students with higher parental education levels tend to have better average scores
- Academic support from educated parents may positively impact performance

👨‍🎓 Gender-Based Performance Analysis

Scores were compared between male and female students.

Key Findings:

- Female students tend to perform better in reading and writing
- Male students perform slightly better in math
- Overall performance differences are moderate but noticeable

🔥 Correlation Analysis

A correlation heatmap was generated to examine relationships between subjects.

Important Observations:

- Reading and Writing scores have very strong correlation
- Math also correlates positively with both subjects
- This suggests that students performing well in one subject are likely to perform well   in others

📈 Subject Relationship (Scatterplots)

Scatterplots were used to analyze relationships between subject scores.
- Math vs Reading
- Shows a positive linear relationship.
- Math vs Writing
- Indicates that students scoring high in math also tend to score well in writing.
- Reading vs Writing
- This pair shows the strongest relationship, confirming the correlation heatmap.

📊 Key Insights

✔ Reading and writing scores are highly correlated
✔ Female students generally perform better in language-based subjects
✔ Students with higher parental education levels tend to perform better
✔ Score distributions are approximately normal
✔ Academic subjects are positively correlated with each other

📁 Project Structure

Student_Performance
│
├── Dataset.csv
├── Project.ipynb
├── README.md
├── Output.png

💡 Future Improvements

Some possible extensions of this project include:

- Building Machine Learning models to predict student scores
- Feature engineering to create performance indicators
- Implementing classification models to predict pass/fail outcomes
- Creating an interactive dashboard using Plotly or Power BI

🧑‍💻 Author

Prasoon Kumar

Aspiring Data Scientist / Machine Learning Engineer

⭐ If you found this project useful, consider starring the repository.