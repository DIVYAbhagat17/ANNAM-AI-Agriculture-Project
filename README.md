
# 🌾 AI-Based Crop Yield Prediction

### ANNAM.AI — Fundamentals of AI Using Agriculture Dataset

An introductory Artificial Intelligence and Machine Learning project that explores agricultural data and predicts crop yield using a **Random Forest Regression** model.

The project demonstrates how machine learning can analyse farming conditions and estimate crop yield based on selected agricultural features.

---

## 📌 Project Overview

Agriculture is influenced by several factors, including plot size, rainfall, fertilizer usage, and temperature. Understanding the relationship between these factors and crop yield can help demonstrate the potential of data-driven agricultural analysis.

This project builds a basic machine learning workflow to analyse agricultural data, visualise patterns, train a regression model, evaluate its performance, and generate crop yield predictions.

## 🎯 Objectives

- Understand and analyse an agricultural dataset.
- Perform basic data cleaning and exploratory data analysis.
- Visualise agricultural variables and their relationships.
- Train a Random Forest Regression model.
- Evaluate model performance using regression metrics.
- Predict crop yield for user-provided farming conditions.
- Implement a simple question-answering feature for dataset statistics.

## 🗂️ Project Structure

```text
ANNAM-AI-Agriculture-Project/
│
├── Agriculture_AI_Project.ipynb
├── Agriculture_AI_Dataset.csv
├── ANNAM_AI_Agriculture_Project_Report.pdf
└── README.md
```

*Note: The report filename may differ depending on your final submitted file.*

## 📊 Dataset Description

The dataset contains **240 records and 6 columns**.

| Feature | Description |
|---|---|
| Farmer_ID | Identifier for each farmer record |
| Plot_Size_acre | Size of the agricultural plot in acres |
| Rainfall_mm | Rainfall in millimetres |
| Fertilizer_kg | Fertilizer quantity in kilograms |
| Avg_Temp_C | Average temperature in °C |
| Yield_quintal | Crop yield in quintals; prediction target |

**Dataset note:** This is a synthetically generated educational dataset. It is not an official or real-world agricultural dataset.

## ⚙️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Random Forest Regression

## 🔬 Methodology

1. Import the required Python libraries.
2. Load and inspect the dataset.
3. Check for missing values and perform basic cleaning.
4. Conduct exploratory data analysis and visualisation.
5. Select input features and the target variable.
6. Split the data into training and testing sets.
7. Train a Random Forest Regression model.
8. Evaluate the model using regression metrics.
9. Analyse feature importance.
10. Generate crop yield predictions and answer basic dataset questions.

## 📈 Dataset Observations

| Observation | Value |
|---|---:|
| Average crop yield | 41.22 quintals |
| Minimum crop yield | 1.16 quintals |
| Maximum crop yield | 109.21 quintals |
| Average rainfall | 725.36 mm |
| Average temperature | 27.52 °C |
| Average fertilizer quantity | 100.84 kg |

These statistics describe the generated dataset and should not be interpreted as actual agricultural statistics.

## 🧪 Sample Prediction

For the following input conditions:

- **Plot size:** 5 acres
- **Rainfall:** 800 mm
- **Fertilizer quantity:** 100 kg
- **Average temperature:** 28 °C

The trained model returned an estimated crop yield of **64.74 quintals**.

This is a model-generated estimate, not a guarantee of actual crop production.

## 🚀 How to Run the Project

1. Open the Jupyter notebook in Google Colab.
2. Upload `Agriculture_AI_Dataset.csv` when prompted.
3. Run the notebook cells in order.
4. Review the data analysis and visualisations.
5. Train and evaluate the model.
6. Enter farming conditions when prompted to obtain a crop yield estimate.

## ⚠️ Limitations

- The dataset is synthetic and intended for educational use.
- Predictions do not establish real-world agricultural accuracy.
- Actual crop yield depends on additional factors such as soil quality, crop variety, irrigation, pests, and farming practices.
- Real agricultural data and domain-specific validation are needed before practical use.

## 🔮 Future Improvements

- Use a documented dataset from a reliable agricultural source.
- Include soil type, crop variety, humidity, and irrigation data.
- Compare multiple regression algorithms.
- Improve model validation and prediction reliability.
- Develop a simple web interface for farmers and agricultural researchers.

## 📚 References

- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/)
- [Google Colab](https://colab.research.google.com/)

## 👩‍💻 Project Information

**Project:** AI-Based Crop Yield Prediction  
**Programme:** ANNAM.AI — Fundamentals of AI Using Agriculture Data Set  
**Platform:** Google Colab  
**Model:** Random Forest Regression

---

*Developed as an educational project to explore the applications of Artificial Intelligence and Machine Learning in agriculture.*
