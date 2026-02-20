# 🚢 Titanic Survival Analysis – Collaborative Data Science Project

## 📌 Project Overview
This project analyzes the Titanic passenger dataset to explore the factors that influenced survival outcomes.

The analysis was conducted using Python and Jupyter Notebooks, focusing on data loading, cleaning, exploratory data analysis (EDA), and visualization.

In addition to the analytical component, this project demonstrates collaborative development using Git and GitHub, including pull requests, branch management, merge conflict testing, and basic workflow automation with GitHub Actions.

---

## 🎯 Project Objective
The objective of this study is to evaluate how demographic and socioeconomic variables affected passenger survival.

The analysis focuses on:

- Passenger class (Pclass)
- Gender (Sex)
- Age
- Fare paid
- Family relationships aboard (SibSp and Parch)

Through exploratory analysis, we aim to identify meaningful patterns within the dataset.

---

## 📊 Dataset Description
The dataset contains passenger-level records including:

- **PassengerId** – Unique passenger identifier  
- **Survived** – Survival outcome (0 = Did not survive, 1 = Survived)  
- **Pclass** – Ticket class (1st, 2nd, 3rd)  
- **Sex** – Gender  
- **Age** – Passenger age  
- **SibSp** – Number of siblings/spouses aboard  
- **Parch** – Number of parents/children aboard  
- **Fare** – Ticket fare  
- **Embarked** – Port of embarkation  

The repository includes both the original dataset and a cleaned version prepared for analysis.

---

## 📂 Repository Structure

- `titanic.csv` – Original dataset  
- `titanic - titanic_cleaning.csv` – Cleaned dataset  
- `titanic - metrics (1).csv` – Analysis metrics  
- `Titanic_code.ipynb` – Main analysis notebook  
- `Test_Code_Error.ipynb` – Testing notebook  
- `.github/workflows/titanic.yml` – GitHub Actions workflow configuration  

---

## 🔧 Git & GitHub Workflow
The project was developed using multiple branches to support collaborative work.

- Feature branches were created for individual tasks.
- Pull requests were used to review and merge contributions.
- Merge conflict testing was performed to understand conflict resolution.
- Contributions were reviewed through pull requests before being merged into the `main` branch.

A basic GitHub Actions workflow was configured to run automatically on pushes and pull requests to the `main` branch.

---

## 👥 Team Members

- Maria Marquelio – Project Leader  
- Gabriel Veneziani – Documentation  
- Eduardo Carreno – Data Cleaning & Analysis  
- Simon – Visualization & Git Workflow Demonstration  

---

## 📈 Learning Outcomes
Through this project, we developed:

- Practical experience with data preprocessing and exploratory analysis  
- Interpretation of survival trends in historical data  
- Hands-on experience with Git branches and pull requests  
- Understanding of merge conflicts and collaborative workflows  
- Basic exposure to GitHub Actions automation  
