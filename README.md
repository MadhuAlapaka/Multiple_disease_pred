# 🩺 Multiple Disease Prediction System using Machine Learning and Streamlit

This project is a **Multiple Disease Prediction System** built using **Machine Learning** techniques in **Python**, deployed with a user-friendly **Streamlit web interface**. It is designed to predict the risk of multiple diseases including **Diabetes, Heart Disease, Parkinson's Disease, Kidney Disease, and Hepatitis** using clinical or lab report data. The system aims to aid in early diagnosis and assist healthcare providers and individuals with proactive disease management.

---

## 🚀 Features

- ✅ Predicts risk for **multiple diseases** from health metrics.
- ⚙️ Utilizes **multiple machine learning models**, optimized for each disease.
- 📊 Performs **data preprocessing** and **feature engineering** for enhanced accuracy.
- 📈 Uses **cross-validation** and evaluation metrics to fine-tune models.
- 🖥️ Deployed on **Streamlit** for a clean, interactive user interface.
- 🔐 Keeps user data local (no data stored on servers).

---

## 🧠 Machine Learning Models Used

- **Support Vector Machine (SVM)**
- **Random Forest**
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes**
- Model selection is based on best performance for each disease dataset.

---

## 📁 Project Structure

├── app.py # Main Streamlit app ├── requirements.txt # Python dependencies ├── README.md # Project description ├── models/ # Trained models (.pkl files) ├── data/ # Datasets used for training ├── utils/ # Helper functions (preprocessing, feature selection) └── images/ # UI screenshots or demo images (optional)

yaml
Copy
Edit

---

## 📊 Datasets Used

We sourced clean and reliable datasets from:

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- [Kaggle Public Datasets](https://www.kaggle.com/)
- Clinical and lab report datasets (CSV format)

Each dataset undergoes:
- **Cleaning** (handling missing values, removing duplicates)
- **Preprocessing** (scaling, encoding)
- **Feature selection/engineering**

---

## 🛠️ Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/multiple-disease-prediction.git
   cd multiple-disease-prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the app locally:

bash
Copy
Edit
streamlit run app.py
💻 Usage
Launch the app using the command above.

Select the disease prediction module (e.g., Heart, Diabetes).

Input your medical metrics (e.g., Glucose Level, Blood Pressure).

View the prediction result and health recommendation instantly.

🧪 Technologies Used
Python

Streamlit

Pandas, NumPy

Scikit-learn

Matplotlib / Seaborn (for visualization)

Joblib / Pickle (for model persistence)

📌 Future Work
Integration with EHR systems

Adding more diseases (e.g., Liver, Lung Cancer)

Support for image-based diagnostics (X-rays, MRIs)

Cloud deployment (Heroku, AWS)

🙋‍♂️ Contributing
Contributions are welcome! If you'd like to improve or extend the project, please follow these steps:

Fork the repository.

Create a new branch: git checkout -b feature-name.

Commit your changes and push: git push origin feature-name.

Open a pull request.

📬 Contact
For queries or collaborations, feel free to reach out:

Madhu Alapaka

Email: alapakamadhusudhanbabu786@gmail.com

LinkedIn: https://www.linkedin.com/in/madhusudhan7022786/
