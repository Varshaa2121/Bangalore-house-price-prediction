# 🏠 Bangalore House Price Prediction

This project is an **end-to-end Machine Learning and web development solution** designed to **predict house prices in Bangalore** based on user inputs such as square footage, number of bedrooms, location, etc. It demonstrates how machine learning models can be trained, evaluated, and deployed in a real-world scenario, and made accessible to end-users through a simple web interface.

---

## 📌 Features

### Machine Learning Model
- Linear regression model trained on a real-world Bangalore housing dataset.
- Predicts prices based on features like **location, size, number of bathrooms, and square footage**.
- Includes **data preprocessing, feature engineering, outlier removal, model evaluation, hyperparameter tuning, and cross-validation**.

### Flask Backend Server
- Python **Flask server** exposes the model via an API.
- Processes user input from the frontend and returns predicted prices.

### Frontend Interface
- Simple web interface built with **HTML, CSS, and JavaScript**.
- Allows users to input property details and view predicted prices in real time.

### End-to-End Flow
1. User enters property details on the frontend.  
2. Data is sent to the Flask backend.  
3. The ML model processes the input.  
4. Predicted price is returned and displayed on the UI.

---

## 🛠 Project Includes
- Data preprocessing and cleaning using **Pandas**  
- Data visualization using **Matplotlib**  
- Outlier detection and removal  
- Feature engineering and dimensionality reduction  
- Model building and evaluation using **scikit-learn**  
- Hyperparameter tuning using **GridSearchCV**  
- Cross-validation using **K-Fold**  
- Model serialization using **pickle**  
- Building a REST API using **Flask**  
- Frontend development with **HTML, CSS, and JavaScript**  
- Full integration of machine learning with web applications

---

## 📦 Note on Pickle File
The trained model file (`bangalore_home_prices_model.pkl`) is **not included** in this repository due to GitHub size limits.

**Instructions for others:**
1. Run the notebook to train the model.  
2. Save the trained model using **pickle** or **joblib**.  
3. Place the file in the appropriate folder for the app to work.
