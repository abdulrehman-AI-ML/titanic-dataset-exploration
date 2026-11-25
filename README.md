# titanic-dataset-exploration

Titanic Data Analysis with Pandas
A beginner-friendly exploration of the Titanic passenger dataset using pandas. This project answers 20 practice questions covering data basics, missing values, filtering, groupby analysis, and feature engineering.
Dataset
The dataset has 891 passengers and 12 columns: PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, and Embarked.
Questions Covered
•	Basics: shape, data types, age statistics, and gender counts.
•	Missing values: finding them, filling Age with the median, filling Embarked with the most common port, and deciding what to do with Cabin.
•	Filtering: survivors, first-class women, older survivors, and the highest fare.
•	Groupby analysis: survival rates by sex and class, average fare by class, and survivors by port.
•	New columns: FamilySize, AgeGroup, passenger Title, and the top 10 fares.
Key Findings
•	342 of 891 passengers survived (38%).
•	Women survived at 74.2% versus 18.9% for men.
•	Survival by class: first 63.0%, second 47.3%, third 24.2%.
•	Average fare by class: first 84.15, second 20.66, third 13.68.
•	Southampton had the most survivors (217), mostly because it had the most passengers.
•	Children (12 and under) had the best survival rate at 58%, while adults had the most survivors in total (243).
•	Cabin was missing for 77% of passengers, so it was dropped.
Tools Used
•	Python
•	pandas
•	Jupyter Notebook
Project Structure
•	data/raw/Titanic-Dataset.csv (the original, untouched file)
•	data/cleaned/titanic_cleaned.csv (the cleaned version created by the notebook)
•	titanic_analysis.ipynb
•	README.md
•	requirements.txt
How to Run
1.	Clone this repository.
2.	Install the requirements with pip install -r requirements.txt.
3.	Open titanic_analysis.ipynb in Jupyter Notebook.
4.	Run all cells.
What I Learned
Cleaning missing values, filtering rows, grouping and aggregating, creating new columns, and extracting text with regular expressions.
Author
Abdulrehman, https://github.com/abdulrehman-AI-ML
