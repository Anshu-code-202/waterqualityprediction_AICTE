
#  Water Pollutants Predictor – AICTE Internship Project

This project is developed as part of the **AICTE Virtual Internship** program. It predicts **water pollution levels** using a Machine Learning model based on chemical parameters of water samples.

---

##  Problem Statement

Traditional water quality testing is often:
- **Time-consuming**
- **Costly**
- **Requires specialized infrastructure and experts**

This project proposes a **machine learning-based solution** to automatically predict pollutant concentrations using accessible chemical data — providing a faster and low-cost alternative.

---

##  Objectives

✅ Clean and preprocess the dataset  
✅ Handle missing values appropriately  
✅ Train a **Random Forest Regressor** on pollutant data  
✅ Evaluate the model using **RMSE** and **R² score**  
✅ Build an interactive **Streamlit web application** for real-time predictions  
✅ Demonstrate a scalable and affordable ML-based approach

---

##  Dataset & Features

- **Dataset file**: `dataset.csv`
- **Target variables**: Concentrations of various pollutants
- **Input features**:
  - Dissolved Oxygen (O₂)
  - Nitrate (NO₃)
  - Nitrite (NO₂)
  - Sulfate (SO₄)
  - Phosphate (PO₄)
  - Chloride (Cl)

>  You can replace or extend features depending on the dataset you’re using. Make sure to preprocess them accordingly.

---

##  Model Information

- **Model Type**: Supervised Regression
- **Algorithm Used**: `RandomForestRegressor`
- **Evaluation Metrics**:
  - R² Score
  - Root Mean Squared Error (RMSE)
- **Tools/Libraries**:
  - Python
  - Pandas, NumPy
  - Scikit-learn
  - Jupyter Notebook
  - Streamlit
  - GitHub

---

##  Streamlit Web App

An interactive web application is built using **Streamlit**, allowing users to enter chemical measurements and get real-time predictions of pollutant levels.

###  To Run Locally:
```bash
pip install -r requirements.txt
streamlit run app.py


##  GitHub Link for Submission
[https://github.com/Anshu-code-202/waterqualityprediction_AICTE](https://github.com/Anshu-code-202/waterqualityprediction_AICTE)

