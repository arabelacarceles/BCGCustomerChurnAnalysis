# Customer Churn Analysis - Business Challenge I

This repository contains the files and documentation for the Business Challenge I project completed during the master's program. The project was provided by Boston Consulting Group (BCG) and focuses on customer churn in the insurance sector. The goal was to analyze data, identify churn patterns, and propose strategies to mitigate churn.

## Project Overview
In this Business Challenge, we worked with synthetic data and a mobile app prototype provided by BCG. The objective was to:
1. Identify key drivers of customer churn.
2. Develop machine learning models to predict churn.
3. Propose actionable strategies to reduce churn.

## Repository Structure
```
├── data/
│   ├── raw/
│   │   ├── insurance_churn_students.csv  # Raw dataset provided by BCG.
│   ├── processed/
│   │   ├── processed_dataset.csv         # Dataset after cleaning and feature engineering.
├── notebooks/
│   ├── MBAN_Team4_BusinessChallenge.ipynb  # Jupyter notebook for data exploration and modeling.
├── models/
│   ├── MBAN_Team4_MLModel_BusinessChallenge.zip  # Machine learning models applied to predict churn.
├── reports/
│   ├── MBAN_Team4_BusinessChallenge_Presentation.pdf  # Final presentation with strategies and insights.
│   ├── MBAN_Team4_BusinessChallenge_Excel.xlsx        # Supporting analysis in Excel.
├── README.md
```

## Steps to Reproduce
### Prerequisites
- Python 3.8 or higher.
- Required Python libraries 
- Jupyter Notebook for running the analysis.
- RapidMinder for Machine Learning Models

### Steps
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your_username/BusinessChallengeI.git
   ```
2. **Data Exploration and Cleaning:**
   - Use the Jupyter notebook `MBAN_Team4_BusinessChallenge.ipynb` to explore and clean the dataset.
3. **Run Machine Learning Models:**
   - Unzip the models in the `models/` folder.
   - Import de models into RapidMinder
4. **Review Results:**
   - Refer to the `reports/` folder for the presentation and supporting analysis.

## Key Deliverables
1. **Data Insights:**
   - Identified key churn drivers such as late payments and customer complaints.
2. **Machine Learning Models:**
   - Applied logistic regression, decision trees, and random forest algorithms to predict churn.
   - Models struggled with accuracy due to the synthetic nature of the dataset.
3. **Strategies:**
   - Developed actionable strategies to reduce churn, including:
     - Automated alerts for missed payments.
     - Gamified engagement and loyalty programs.
     - Improved onboarding and claims processing.

## Technologies Used
- **Programming Languages:** Python, Jupyter Notebook.
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
- **Tools:** RapidMiner for machine learning models, Excel for additional analysis.


## Notes
- This project is purely educational and was part of Business Challenge I during the Fall Term of the MBA with Analytics program at Hult International Business School.
- The dataset is synthetic and provided by BCG for academic purposes only.
- Strategies and insights were based on the analysis of synthetic data and are illustrative.

## License
This project is for educational purposes only and is licensed under the Educational Community License v2.0 (ECL-2.0). 
All rights, including intellectual property, remain with the authors: 
  Arabela Cárceles, Melek Ladhari, Sayefaldeen Suleiman, Abhimanyu Kankhar, Ansh Patek, and Fernando Caballol.

### Usage Restrictions
- Redistribution, modification, or commercial use of the contents in this repository is strictly prohibited without prior written consent from the authors.
- The dataset and insights were created for academic purposes and should not be used in real-world applications.
- This repository is intended to be used exclusively for educational and non-commercial research.
