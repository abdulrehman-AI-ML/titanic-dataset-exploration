# Titanic Data Analysis with Pandas

A beginner-friendly exploration of the Titanic passenger dataset using **pandas**. This project answers 20 practice questions covering data basics, missing values, filtering, groupby analysis, and feature engineering.

---

## 📊 Dataset
The dataset contains **891 passengers** and **12 columns**:
`PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, and `Embarked`.

---

## 🔍 Questions Covered
* **Basics:** Shape, data types, age statistics, and gender counts.
* **Missing Values:** Identifying nulls, filling `Age` with the median, filling `Embarked` with the most common port, and deciding how to handle `Cabin`.
* **Filtering:** Survivors, first-class women, older survivors, and the highest fare.
* **Groupby Analysis:** Survival rates by sex and class, average fare by class, and survivors by port.
* **Feature Engineering (New Columns):** `FamilySize`, `AgeGroup`, passenger `Title`, and identifying the top 10 fares.

---

## 💡 Key Findings
* **Overall Survival:** 342 of 891 passengers survived (**38%**).
* **Survival by Gender:** Women survived at **74.2%** versus **18.9%** for men.
* **Survival by Class:** First class (**63.0%**), second class (**47.3%**), and third class (**24.2%**).
* **Average Fare by Class:** First class (**\$84.15**), second class (**\$20.66**), and third class (**\$13.68**).
* **Embarkation Port:** Southampton had the most survivors (**217**), largely because it had the highest number of boarding passengers.
* **Survival by Age Group:** Children (12 and under) had the highest survival rate at **58%**, while adults accounted for the highest total number of survivors (**243**).
* **Data Cleaning Decision:** `Cabin` was missing for **77%** of passengers, so the column was dropped.

---

## 🛠️ Tools Used
* Python
* pandas
* Jupyter Notebook

---

## 📁 Project Structure
```text
titanic-dataset-exploration/
├── data/
│   ├── raw/
│   │   └── Titanic-Dataset.csv      # Original, untouched dataset
│   └── cleaned/
│       └── titanic_cleaned.csv      # Cleaned dataset exported from the notebook
├── titanic_analysis.ipynb           # Main Jupyter Notebook with all 20 questions
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. **Clone this repository:**
   ```bash
   git clone https://github.com
   cd titanic-dataset-exploration
   ```

2. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the analysis:**
   Open `titanic_analysis.ipynb` in Jupyter Notebook and run all cells.

---

## 🧠 What I Learned
* Handling and imputing missing values
* Filtering DataFrames with multiple conditions
* Grouping and aggregating data for insights
* Creating new features (`FamilySize`, `AgeGroup`, `Title`)
* Extracting text patterns using regular expressions (regex)

---

## 👤 Author
**Abdulrehman** — [@abdulrehman-AI-ML](https://github.com/abdulrehman-AI-ML)
