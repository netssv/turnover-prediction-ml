# 📊 Employee Turnover Prediction Analysis

## 🎯 Project Description
Machine Learning project to predict employee turnover using data analysis techniques and predictive models. This project follows Kaggle-style best practices for a complete ML workflow.

## 📁 Project Structure
```
├── employee_turnover_prediction_english.ipynb    # Main notebook with complete analysis
├── turnover.csv                                  # Employee dataset
└── README.md                                     # This file
```

## 🛠️ Technologies Used
- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **Scikit-learn** - Machine Learning models
- **Matplotlib/Seaborn** - Data visualizations
- **NumPy** - Numerical computing
- **Jupyter Notebook** - Interactive development

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/netssv/turnover-prediction-ml.git
   cd turnover-prediction-ml
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the notebook:
   ```bash
   jupyter notebook employee_turnover_prediction_english.ipynb
   ```
4. Run all cells to reproduce the analysis

## 📈 Key Results
- **Winner Model**: Random Forest Classifier
- **Accuracy**: 70.8%
- **F1-Score**: 0.723
- **Precision**: 0.750
- **Recall**: 0.698
- **Most Important Features**: Tenure (stag), Age, Industry, Independence, Self-control

## 📋 Methodology (7-Step ML Workflow)
1. **Problem Definition** - Target variable and research question
2. **Data Loading** - Initial dataset exploration
3. **EDA** - Comprehensive exploratory data analysis
4. **Data Preparation** - Preprocessing and feature engineering
5. **Data Splitting** - Stratified train/test split (80/20)
6. **Base Model** - Random Forest as baseline
7. **Model Comparison** - Performance evaluation vs Logistic Regression

## 🎯 Practical Applications
- **HR Analytics**: Identify employees at risk of leaving
- **Retention Strategies**: Focus on key factors that drive turnover
- **Predictive Insights**: Proactive workforce management
- **Cost Reduction**: Minimize recruitment and training costs

## 📊 Dataset Information
- **Size**: 1,129 employees
- **Features**: 16 characteristics (personal and work-related)
- **Target**: Binary classification (0 = stays, 1 = leaves)
- **Balance**: Well-balanced dataset (50.6% turnover rate)

## 🔍 Key Features Analyzed
- **Demographics**: Age, Gender
- **Work Experience**: Tenure (stag), Industry, Profession
- **Psychological Traits**: Anxiety, Extraversion, Independence, Self-control, Innovation
- **Work Environment**: Traffic, Coach, Head Gender, Way of working

## 💡 Practical Examples Included
- **Individual Predictions**: Examples like "John Smith" employee profile
- **Risk Assessment**: High/Medium/Low risk categorization
- **Feature Importance**: Understanding what drives turnover decisions
- **Probability Scores**: Confidence levels for each prediction

## 👥 Author
- **Name**: Rodrigo Martel
- **Course**: Kodigo - Python Module 2
- **Project**: Employee Turnover Prediction

## 📄 License
This project is for educational use - Kodigo 2025

## 🌟 Perfect for Learning
- 🎓 **ML Fundamentals**: Complete workflow from data to model
- 💼 **HR Analytics**: Real-world employee retention problem
- 📊 **Data Science**: Best practices and reproducible analysis
- 🔬 **Predictive Modeling**: Practical machine learning application

