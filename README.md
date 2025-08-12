# 🚖 Driver Attrition Prediction (Ola, Uber, Rapido)

Driver attrition is a major challenge in the ride-hailing industry, affecting efficiency and growth.  
Ola faces high churn rates as drivers switch to competitors like Uber, leading to service disruptions and increased costs.  
This project applies data science to predict attrition using historical driver data, leveraging **Bagging** and **Boosting** techniques along with preprocessing steps like **KNN imputation** and feature engineering.  
The goal is to build a predictive model that helps Ola retain drivers and optimize operations.

---

## 🔍 Features
- Driver attrition prediction using **Random Forest** and **Gradient Boosting** models.
- Comparison of attrition trends across **Ola**, **Uber**, and **Rapido**.
- Data visualization using **pie charts**, **bar plots**, and other statistical graphics.
- CSV data processing and cleaning.
- Flask-based web application with:
  - **Home Page**
  - **Data Comparison Page**
  - **Prediction Results Page**

---

## ⚙️ Technologies Used
- Python
- Flask
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- HTML, CSS

---

## 🧠 Models Used
- **Random Forest Classifier** – Ensemble learning for robust prediction.
- **Gradient Boosting Classifier** – Boosted trees for improved accuracy.

---

## 🚀 How to Run
```bash
# Run the Flask App
python app4.py
Visit: http://127.0.0.1:5000/ in your browser.

```
## 📁 Project Structure
```bash
driver-attrition-prediction/
│
├── data/                      # Raw/processed data (optional)
│   ├── Ola2.csv
│   ├── rapido.csv
│   ├── uber.csv
│
├── static/                    # CSS and static assets
│   ├── dashboardstyle.css      # For comparison.html
│   ├── styles.css              # For index.html
│
├── templates/                 # HTML templates for Flask
│   ├── index.html              # Homepage
│   ├── comparison.html         # Data comparison & visualization
│   └── result.html             # Prediction output
│
├── app4.py                    # Main Flask application
├── ola.csv                    # Ola dataset
├── uber.csv                   # Uber dataset
├── rapido.csv                 # Rapido dataset
└── README.md                  # Documentation
