#  Machine Learning on Global Terrorism Analysis
<img width="1364" height="802" alt="image" src="https://github.com/user-attachments/assets/a0010c73-8cf3-4ffa-bbec-d564228efd24" />


##  Project Overview
This project applies machine learning techniques to analyze global terrorism data and predict whether a terrorist attack will be successful. The model uses features such as year, month, country, region, attack type, target type, and weapon type to identify patterns in historical incidents. The goal is to support data-driven insights for understanding terrorism trends and improving risk assessment.

---

##  Dataset Details
- **Dataset:** Global Terrorism Database (GTD)  
- **Description:** Historical dataset containing worldwide terrorist incidents  

### Key Features Used:
- `iyear` – Year of attack  
- `imonth` – Month of attack  
- `country_txt` – Country  
- `region_txt` – Region  
- `attacktype1_txt` – Attack type  
- `targtype1_txt` – Target type  
- `weaptype1_txt` – Weapon type  
- `success` – Target variable (0 = Failed, 1 = Successful)  

###  Data Preprocessing:
- Removed missing values  
- Selected relevant features  
- Encoded categorical variables for model training  

---

##  Approach

### 1️. Data Cleaning & Preprocessing
- Handled missing values using `dropna()`  
- Converted categorical variables using encoding techniques  

### 2️. Exploratory Data Analysis (EDA)
- Identified high-risk regions  
- Analyzed trends in attack types and weapon usage  

### 3️. Model Building
- Logistic Regression  
- Decision Tree  
- Random Forest  

### 4️. Model Evaluation
- Accuracy Score  
- Confusion Matrix  

---

## 📈 Results & Insights
- Random Forest performed best among all models due to its ability to handle complex patterns  
- Certain regions show significantly higher attack frequencies  
- Specific combinations of attack type and weapon type increase the probability of success  
- The model can effectively predict attack success for analytical purposes  

---

## Tools & Technologies Used
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Visualization:** Power BI / Matplotlib  
- **Environment:** Jupyter Notebook  

---

## Future Scope
- Improve accuracy using advanced models like XGBoost or Neural Networks  
- Deploy the model using Flask or Streamlit  
- Integrate real-time data for live predictions  

---

## Author
**Mayur Shewale**
