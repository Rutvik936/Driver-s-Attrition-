# Driver Attrition Prediction (Ola, Uber, Rapido)

This is a web-based machine learning application designed to predict and analyze driver attrition for ride-sharing platforms like Ola, Uber, and Rapido. The project uses real-world data, performs preprocessing, visualizations, and predictive modeling using Random Forest and Gradient Boosting.

## 🔍 Features

- Driver attrition prediction using ML models (Random Forest, Gradient Boosting)
- Comparison of attrition trends across Ola, Uber, and Rapido
- Visual representation of attrition statistics using pie charts, bar plots, etc.
- CSV data processing and data cleaning
- Flask-based web interface with pages for:
  - Home
  - Data comparison
  - Prediction results


## ⚙️ Technologies Used

- Python
- Flask
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- HTML, CSS

## 🧠 Models Used

- **Random Forest Classifier** – Ensemble model for robust prediction
- **Gradient Boosting Classifier** – Boosted trees for improved accuracy

**Run the Flask App**

**command:**  python app4.py
**Visit** http://127.0.0.1:5000/ in your browser.

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

