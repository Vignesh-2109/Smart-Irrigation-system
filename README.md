# 🌿 Smart Irrigation System 🚰

![NodeMCU](https://img.shields.io/badge/NodeMCU-ESP8266-orange)
![ThingSpeak](https://img.shields.io/badge/ThingSpeak-IoT-blue)
![Blynk](https://img.shields.io/badge/Blynk-App-green)
![Logistic Regression](https://img.shields.io/badge/ML-Logistic%20Regression-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 📜 Overview

A Smart Irrigation System has been developed utilizing **NodeMCU** as the microcontroller and sensors such as **temperature** and **soil moisture** to collect the necessary data. The incorporation of NodeMCU has enabled us to transmit the data to the cloud effortlessly, thanks to its built-in WiFi module.

## 🧠 Edge Computing & Machine Learning

The collected data is analyzed using a **machine learning algorithm** within the NodeMCU itself. This implementation of Edge Computing has significantly improved the speed of obtaining results. Through our experimentation, we have found that **Logistic Regression** yields the best results.

## 🚀 How It Works

1. **Data Collection**: Sensors gather temperature and soil moisture data.
2. **Data Transmission**: NodeMCU transmits the data to the cloud.
3. **Data Analysis**: Machine learning algorithm predicts water requirements.
4. **Irrigation Control**: Water pump turns on/off based on the prediction.

## 📊 Data Storage & Access

- **Database**: The database will be stored in **ThingSpeak**.
- **User Access**: Users can access the data using the **Blynk app**.

## 📱 Blynk App

![Blynk](https://img.shields.io/badge/Blynk-App-green)

Monitor and control your irrigation system remotely using the Blynk app.

## 💻 Hardware Components

- **NodeMCU** (ESP8266)
- **Temperature Sensor**
- **Soil Moisture Sensor**
- **Water Pump**

## 🔧 Software Components

- **Arduino IDE** for programming NodeMCU
- **ThingSpeak** for data storage and visualization
- **Blynk** for remote access

## 📈 Machine Learning

![Logistic Regression](https://img.shields.io/badge/ML-Logistic%20Regression-brightgreen)

We have implemented Logistic Regression on the NodeMCU for real-time prediction and analysis.

## 🚧 Setup Instructions

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/smart-irrigation-system.git
    cd smart-irrigation-system
    ```

2. **Install Dependencies**:
    - Arduino IDE
    - Blynk Library
    - ThingSpeak Library

3. **Upload Code to NodeMCU**:
    - Open the project in Arduino IDE.
    - Configure your WiFi credentials and ThingSpeak API keys.
    - Upload the code to NodeMCU.

4. **Set Up Blynk App**:
    - Create a new project in the Blynk app.
    - Add widgets for monitoring temperature, soil moisture, and controlling the pump.
    - Link your NodeMCU to the Blynk app using the provided authentication token.

## 📚 Documentation

- [ThingSpeak Documentation](https://thingspeak.com/docs)
- [Blynk Documentation](https://docs.blynk.io)
- [NodeMCU Documentation](https://nodemcu.readthedocs.io)



Developed with ❤️ by [Vigensh Maram](https://github.com/Vignesh-2109)
