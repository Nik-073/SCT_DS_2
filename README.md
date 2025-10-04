# SCT_DS_2
Task 2 : Data Cleaning and Eexploratory Data Analysis
🚢 Titanic Data Cleaning & Exploratory Data Analysis (EDA)

🔹 Project Overview

This task demonstrates data cleaning and exploratory data analysis (EDA) on the Titanic dataset. The goal is to uncover meaningful insights about passenger survival patterns by analyzing various features like age, gender, class, and fare.

🎯 Objectives

Clean the dataset by handling missing values, correcting data types, and removing inconsistencies.

Perform EDA to explore relationships between features and passenger survival.

Visualize trends using bar charts, histograms, and heatmaps.

Extract actionable insights about factors influencing survival rates.

🗂 Dataset

Source:https://www.kaggle.com/datasets/yasserh/titanic-dataset

Key Features:

PassengerId, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

Target: Survived

Note: Dataset requires preprocessing due to missing and categorical data.

⚙️ Requirements

Python 3.x

Libraries:

pandas

numpy

matplotlib

seaborn

Install dependencies:

pip install -r requirements.txt

🚀 Usage

Clone the repository:

git clone <repository-url>


Navigate to project folder:

cd titanic-data-cleaning-eda


Run the script:

python titanic_eda.py

📊 Example Insights & Visualizations
Survival Count

Survival by Gender

Age Distribution of Passengers

These visualizations reveal key survival patterns such as higher survival for females and first-class passengers.

🏗 Project Structure
titanic-data-cleaning-eda/
│
├── titanic.csv             # Dataset file
├── titanic_eda.py          # Python script for cleaning & EDA
├── images/                 # Folder containing visualizations
├── README.md               # Project documentation
└── requirements.txt        # Required Python libraries

