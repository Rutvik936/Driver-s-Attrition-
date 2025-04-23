# Driver Attrition Prediction (Ola, Uber, Rapido)

Driver attrition is a major challenge in the ride-hailing industry, affecting efficiency and growth. 
Ola faces high churn rates as drivers switch to competitors like Uber, leading to service disruptions and increased costs. 
This study applies data science to predict attrition using historical driver data.
 Machine learning techniques, including Bagging and Boosting, are used with preprocessing steps like KNN imputation and feature engineering. 
The goal is to develop a predictive model that helps Ola retain drivers and optimize operations.

-------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔍 Features

- Driver attrition prediction using ML models (Random Forest, Gradient Boosting)
- Comparison of attrition trends across Ola, Uber, and Rapido
- Visual representation of attrition statistics using pie charts, bar plots, etc.
- CSV data processing and data cleaning
- Flask-based web interface with pages for:
  - Home
  - Data comparison
  - Prediction results

-------------------------------------------------------------------------------------------------------------------------------------------------------

## ⚙️ Technologies Used

- Python
- Flask
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- HTML, CSS

-------------------------------------------------------------------------------------------------------------------------------------------------------

## 🧠 Models Used

- **Random Forest Classifier** – Ensemble model for robust prediction
- **Gradient Boosting Classifier** – Boosted trees for improved accuracy
-------------------------------------------------------------------------------------------------------------------------------------------------------
**Run the Flask App**

**command:**  python app4.py

**Visit** http://127.0.0.1:5000/ in your browser.

-------------------------------------------------------------------------------------------------------------------------------------------------------
## 📁 Project Structure
Project Structure:

driver-attrition-prediction/
│
├── data/                      # Folder for raw/processed data (optional)
│   ├── Ola2.csv               # Data.csv Files Used for Comparison
│   ├── rapido.csv
│   ├── uber.csv
├── static/                    # Static assets like CSS or images
│   ├── dashboardstyle.css     # css for comparison.html
│   ├── styles.css             # css for index.html
├── templates/                 # HTML templates for Flask
│   ├── index.html             # Homepage
│   ├── comparison.html        # Data comparison and visualization
│   └── result.html            # Model prediction output
│
├── app4.py                    # Main Flask application file
├── ola.csv                    # Ola drivers dataset
├── uber.csv                   # Uber drivers dataset
├── rapido.csv                 # Rapido drivers dataset
├── README.md                  # Project documentation

