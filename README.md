# 🌱 Green BUD: Corn Yield Prediction Desktop App

Green BUD is a cross-platform desktop application that predicts **corn yield productivity** based on real-time **climate** and **soil** features. Powered by an **XGBoost regression model (R² = 0.92)**, the app helps agricultural users make data-driven decisions for better crop management.

---

## 🖥️ Features

- 📍 Select a location via map interface (e.g., Fayoum, Egypt)
- 🌦️ Real-time weather integration (temperature, humidity, etc.)
- 🧪 Input soil features (pH, EC, etc.)
- 📈 Predict corn productivity using a trained ML model 
- ✅ Works fully offline after installation

---

## ⚙️ Tech Stack

- **Model**: XGBoost Regressor
- **Language**: Python
- **GUI**: PySide6 / PyQt
- **ML Libraries**: Scikit-learn, XGBoost, Pandas
- **Packaging**: PyInstaller (for Windows executable)

---

## 📦 Installation (Windows)

1. Download the installer `.exe` file   
2. Run the installer and follow setup instructions
3. Launch the **Green BUD** app from your desktop

---

## 🧠 Model Details

- **Type**: Regression
- **Library**: XGBoost
- **Performance**: R² = 0.92 on validation data
- **Features Used**:
  - Air Temperature (°C)
  - Relative Humidity (%)
  - Wind Speed (m/s)
  - Soil pH
  - Electrical Conductivity (EC, dS/m)

---

## 📷 App Preview

![App Screenshot](https://github.com/Yasmine-Ahmed99/Corn-Prodactivity/blob/main/prediction.jpeg) 

---


## 👨‍🌾 Who is it for?

- Farmers
- Agronomists
- Agricultural researchers
- Policy makers and planners in agri-tech

---

## 🛠️ Developer Notes

- Trained model stored as: `corn_yield_model.pkl`
- GUI built using PySide6
- Desktop packaging 



