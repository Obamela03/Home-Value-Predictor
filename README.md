# 🏡 Property Price Prediction Platform (Django + XGBoost)

A full-stack machine learning web application for predicting property prices using real estate data and advanced regression techniques.

---

## 📌 Overview

This project is a robust real estate pricing platform that combines the power of machine learning (**XGBoost regression**) with the versatility of the **Django** web framework. It allows users to analyze property listings and estimate their value based on multiple features such as size, location, and amenities.

Built as both a local web app and a showcase-ready GitHub repository, the project reflects a strong integration of data science and full-stack development practices.

---

## ⚙️ Features

- ✅ **Price Prediction with XGBoost**: Uses a well-tuned XGBoost regression model for accurate property price prediction.
- 📁 **Admin CSV Upload Panel**: Django Admin dashboard extended to allow uploading new training data (CSV) directly.
- 🔁 **Model Retraining**: Admins can retrain the ML model with new data at the click of a button—no code required.
- 🖼️ **Mock Dataset Support**: Pre-generated synthetic dataset included for demonstration purposes.
- 📊 **Feature Impact Analysis**: Backend measures and visualizes feature contributions (coming soon).
- 📦 **Clean Architecture**: Organized folder structure with separation of concerns (data, model, views, admin).
- 🖥️ **Locally Deployable**: Fully functional on localhost; ideal for demo or portfolio showcasing.
- 🌐 **Open Source Ready**: Hosted on GitHub with clear structure, README, and licensing.

---

## 🛠 Tech Stack

- **Backend**: Python, Django  
- **Machine Learning**: XGBoost, Scikit-learn, Pandas, Joblib  
- **Frontend**: HTML/CSS (Admin UI customization)  
- **Data Storage**: SQLite (for dev), CSV for input  
- **Model Management**: Filesystem-based `.joblib` models

---

## 📈 Use Case

Imagine a property manager or agent entering the square footage, number of bedrooms, bathrooms, and area rating—then instantly getting an estimated price based on prior trends. This solution streamlines that process, supports retraining with newer market data, and is extendable for production-scale use.

---

## 🧠 Learning Outcomes

- Real-world implementation of ML model integration in a full-stack web app  
- Django admin customization and form extension  
- Building, saving, and loading models using `joblib`  
- Working with tabular data and applying regression algorithms
