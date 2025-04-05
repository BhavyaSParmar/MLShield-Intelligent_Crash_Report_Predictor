# MLShield-Intelligent_Crash_Report_Predictor

This project focuses on predicting the severity of **driver injuries** and **vehicle damage** using supervised machine learning techniques. The model is trained on a dataset with features such as collision type, traffic conditions, weather, light conditions, and substance involvement.

---

## 🧠 Objective

To build a **robust ML model** that can accurately classify:

- **Injury Severity** (Minor, Serious, Fatal)
- **Vehicle Damage Extent** (None, Moderate, Severe)

---

## 📊 Dataset

The dataset contains detailed crash reports with categorical and numerical attributes. Key features include:

- **Collision Type**
- **Weather Conditions**
- **Road Surface**
- **Light Conditions**
- **Traffic Density**
- **Substance Involvement**
- **Speed Zone**

---

## 🛠️ Tools & Technologies

- **Python** 🐍
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 📈 ML Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost

Each model's performance was evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report

---

## 🔍 Key Findings

- Substance involvement and collision type were strong predictors of crash severity.
- Random Forest and XGBoost yielded the highest accuracy.
- Feature engineering and label encoding significantly improved results.

---

## 📌 Results

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| 70.2%    |
| Decision Tree      | 76.8%    |
| Random Forest      | 83.5%    |
| XGBoost            | **85.1%**|

---

## 📁 Project Structure
├── Crash_Reporting_Prediction_Model_Project_Supervised_Machine_Learning_Python.ipynb
This is the main Jupyter Notebook that holds the entire machine learning workflow.

It includes data loading, preprocessing, exploratory data analysis (EDA), model training, evaluation, and conclusion.

├── README.md
A documentation file that provides an overview of the project, including objectives, tools used, methodology, results, and how to run the project.

Essential for GitHub repositories to help users and collaborators understand the purpose and structure of the project.

└── dataset/
A folder that stores data files used in the project.

└── crash_data.csv
The CSV file containing the raw or processed crash data.

This dataset is the input for the machine learning model and contains features like collision type, road condition, weather, and injury severity.


---

## 📚 References

- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Road Safety Statistics - Public Datasets]

---

## 🌟 Acknowledgments

Thanks to our professors and mentors for their guidance in this project. 🚦

---

## 📫 Contact
Created with ❤️ by Bhavya Parmar, Drop a ⭐ if you like the project!
