# 🔥 Fire Type Classification using MODIS Satellite Data

This project was developed as part of the **Shell–Edunet Foundation Green Skills AICTE Internship** focused on leveraging **AI technologies for environmental challenges**. Over a 4-week guided mentorship program, I independently built a predictive model to classify fire types using MODIS satellite data.

<p align="center">
  <img src="Screenshot%202025-08-01%20180718.png" alt="Fire Type Classification UI" width="700"/>
</p>

---

## 📌 Internship Context

This project was created during the **AICTE–Shell–Edunet Green Skills Internship** (July–August 2025), under expert mentorship, to:
- Apply AI skills to a real-world environmental problem,
- Build a complete data pipeline from preprocessing to model deployment,
- Contribute toward sustainability and fire risk analysis using satellite data.

---

## 🚀 About the Project

This tool takes satellite readings as input and predicts the **type of fire** (e.g., vegetation fire, offshore fire) using a trained ML model. The app is powered by **Streamlit**, built for ease of use, and styled for clarity and interactivity.

---

## 📁 Project Structure

- 📓 `Classification_of_Fire_Types_in_India_Using_MODIS_Satellite_Data_verify.ipynb` – Main notebook used for model training, outlier handling, SMOTE, and evaluation.
- 🧠 `best_fire_detection_model.pkl` – Final trained model.
- 🔧 `scaler.pkl` – StandardScaler used for input normalization.
- 🎨 `app.py` – Streamlit web app with rich UI.
- 📄 `README.md` – You're here!

> 📥 Download the model `.pkl` file from Drive:  
> [📎 Model Link – Google Drive](https://drive.google.com/file/d/1EQbNqtbKpyvHkp1ClBO1qEThG7K0rC_8/view?usp=drive_link)

---

## 🧠 Features

✅ Real-time satellite input processing  
✅ Intuitive UI with tooltips and emoji  
✅ Prediction of fire type using MODIS-derived features  
✅ Supports Brightness, FRP, Confidence, and more  
✅ Trained and tested on data from 2021–2023

---

## 🎯 Model Inputs

- 🔆 Brightness  
- 🌡️ Brightness T31  
- 🔥 Fire Radiative Power (FRP)  
- 🛰️ Scan  
- 📍 Track  
- 🧠 Confidence Level (Low, Nominal, High)

---

## 📦 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fire-type-classification.git
   cd fire-type-classification
## 📦 How to Run Locally

1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
- Place the .pkl model files (best_fire_detection_model.pkl and scaler.pkl) in the root directory.

- Run the Streamlit app:

```bash
streamlit run app.py
```
## 📸 UI Preview

![App Screenshot](screenshot.png)

## 🧑‍💻 Author
Chiranjeevi Sai Moka
🎓 AICTE–Shell–Edunet Internship 2025
🛰️ Passionate about AI for Sustainability

## 📜 License
MIT License – see the LICENSE file for details.

## 🛰️ Acknowledgements
🏢 Edunet Foundation, AICTE, and Shell for the internship opportunity

🛰️ MODIS NASA for open satellite fire data

📦 Scikit-learn, imbalanced-learn, and Streamlit for enabling this project

