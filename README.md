# 🩺 Portable AI-Powered Health Monitoring System for Rural Populations

## 📌 Overview
This project aims to build a **Portable AI-powered Health Monitoring System** using low-cost sensors, Edge AI, and cloud-based analytics to provide **real-time disease risk analysis and telemedicine support** for rural and underserved areas.

---

## 🚀 Features
- **Multi-sensor IoT device** for vitals monitoring (Heart Rate, BP, SpO₂, Temperature, Glucose, Hemoglobin)
- **Edge AI models** for local health risk detection
- **Cloud Sync** for extended storage and analytics
- **LLM-powered health assistant chatbot**
- **Telemedicine integration** using Twilio API
- **Offline-first mobile app** with sync capabilities

---

## 🛠 Tech Stack
- **Hardware:** Raspberry Pi / ESP32, Biomedical Sensors (ECG, PPG, NIR, etc.)
- **Edge AI:** TinyML, TensorFlow Lite
- **AI/ML Frameworks:** TensorFlow, Scikit-learn, Keras
- **Mobile App:** React Native
- **Cloud:** Firebase (Auth + Firestore), Google Cloud Platform (AI models)
- **Video Consults:** Twilio API
- **Data Transfer:** MQTT / HTTP

---

## 📁 Project Structure
```
portable-health-monitoring-ai/
│
├── hardware/
│   └── esp32_sensor_code.ino
├── models/
│   ├── glucose_predictor.pkl
│   └── ecg_cnn_model.tflite
├── app/
│   └── react-native-app-code/
├── backend/
│   └── firebase-functions/
├── chatbot/
│   └── health_assistant_llm.py
├── data/
│   └── sample_vitals.csv
├── docs/
│   ├── architecture_diagram.png
│   └── wireframes/
└── README.md
```

---

## 📊 How It Works
1. **Sensors** collect biometric data
2. **Edge AI** processes it on-device (TinyML)
3. **Real-time alerts** shown on the mobile app
4. If risk is detected:
   - AI chatbot helps user
   - Sync to cloud for detailed prediction
   - Optional video consult via Twilio

---

## 🧠 AI Models
- **ECG CNN** for detecting arrhythmia
- **LSTM for time-series vitals**
- **KNN/SVM for early disease classification**
- **LLM (OpenAI / Gemini)** for chatbot inference

---

## 📞 Contact & Contributions
Feel free to contribute or open issues! 
Made with ❤️ for real-world health impact.
