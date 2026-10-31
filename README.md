# RAINGUARD-District-Wise-Rainfall-Forecasting-and-Heavy-Rainfall-Risk-Analysis-Using-Machine-Learning
# 🌧️ RainGuard
## Indian Rainfall Forecasting and Heavy-Rainfall Risk Analysis System Using District-Wise IMD Data

**RainGuard** is a machine learning and data science project that analyses district-wise daily rainfall data across India to forecast next-day rainfall and classify rainfall intensity.

The project uses historical rainfall observations published by the India Meteorological Department (IMD). It follows an end-to-end data science workflow, including data preprocessing, exploratory data analysis, statistical analysis, feature engineering, machine learning, model optimisation and validation.

---

## 🎯 Project Objectives

- Analyse district-wise rainfall patterns across India.
- Clean and preprocess raw rainfall data.
- Perform Exploratory Data Analysis (EDA).
- Study rainfall distribution, variability and persistence.
- Engineer historical and temporal rainfall features.
- Predict next-day rainfall using regression models.
- Classify next-day rainfall intensity.
- Compare and optimise machine learning models.
- Interpret model performance and identify limitations.

## 📊 Dataset Overview

| Attribute | Details |
|---|---|
| Dataset | District-wise Daily Rainfall |
| Source | India Meteorological Department (IMD) |
| Total Records | 53,102 |
| Raw Columns | 22 |
| Cleaned Columns | 38 |
| Districts | 728 |
| States/UTs | 37 after standardisation |
| Observation Period | 19 August – 30 October 2026 |

The dataset contains daily actual rainfall, normal rainfall, departure percentages, and weekly, cumulative and monthly rainfall information.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualisation:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Development Environment:** Jupyter Notebook

## ⚙️ Project Modules

The project is divided into nine modules:

| Module | Description |
|---|---|
| 01 | Data Preprocessing |
| 02 | Exploratory Data Analysis (EDA) |
| 03 | Statistical Analysis |
| 04 | Feature Engineering |
| 05 | Next-Day Rainfall Regression |
| 06 | Rainfall-Intensity Classification |
| 07 | Model Comparison |
| 08 | Classification Optimisation |
| 09 | Final Model Interpretation and Validation |

## 🤖 Machine Learning Algorithms

### Regression
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

### Classification
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

## 📈 Model Performance

### Best Regression Model

**Gradient Boosting Regressor**

| Evaluation Metric | Result |
|---|---:|
| MAE | 2.9226 mm |
| RMSE | 9.2505 mm |
| R² Score | 0.1633 |

### Optimised Classification Model

| Evaluation Metric | Result |
|---|---:|
| Accuracy | 0.8326 |
| Balanced Accuracy | 0.3401 |
| Macro F1 Score | 0.3108 |

The optimised classifier improved Macro F1 and balanced accuracy compared with the original classification model. However, detecting rare heavy-rainfall categories remains challenging because of class imbalance.

## 📁 Repository Structure

```text
RainGaurd/
│
├── RainGuard_01_Preprocessing.ipynb
├── RainGuard_02_EDA.ipynb
├── RainGuard_03_Statistical_Analysis.ipynb
├── RainGuard_04_Feature_Engineering.ipynb
├── RainGuard_05_Regression.ipynb
├── RainGuard_06_Classification.ipynb
├── RainGuard_07_Model_Comparison.ipynb
├── RainGuard_08_Classification_Optimization.ipynb
├── RainGuard_09_Final_Model_Interpretation_Validation.ipynb
│
├── rainfall_districtwise_daily_imd.csv
├── rainfall_cleaned.csv
│
├── rainguardpic.zip
│
└── README.md
```

## 🚀 How to Run the Project

**1. Clone the repository**

```bash
git clone YOUR_REPOSITORY_URL
```

**2. Open the project directory**

```bash
cd RainGaurd
```

**3. Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

**5. Run the notebooks**

Execute the nine notebooks in sequential order, starting with Module 01: Data Preprocessing.

## ⚠️ Limitations

- The dataset covers 73 days and does not represent a complete annual rainfall cycle.
- Heavy-rainfall observations are significantly underrepresented.
- Regression performance is modest.
- Rare rainfall-intensity categories remain difficult to classify.
- Additional meteorological variables could improve future predictions.

**Note:** RainGuard is an academic rainfall-forecasting and intensity-classification prototype. It is not a validated operational weather-warning or flood-prediction system.

## 🔮 Future Scope

- Integrating multi-year historical rainfall data.
- Including temperature, humidity, wind speed and atmospheric pressure.
- Improving extreme-rainfall classification.
- Developing an interactive district-wise rainfall dashboard.
- Evaluating models on additional independent time periods.

## 👨‍💻 Author

**Musafir Ahmed Choudhury**

B.Tech – Computer Science and Engineering  
Lovely Professional University, Punjab, India.

Registration Number: 12411559

**Project Supervisor:** Dr. Madhubala (31770)

---

⭐ If you find this project interesting, consider giving this repository a star!

