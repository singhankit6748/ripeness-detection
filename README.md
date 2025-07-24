# 🍌 Fruit & Vegetable Ripeness Detection using ESP32-CAM & Edge Impulse

This project uses an **ESP32-CAM** module with a **custom-trained Edge Impulse model** to detect the ripeness stage of fruits and vegetables in real-time. The goal is to automate freshness monitoring in agriculture and food supply chains.

## 🛠️ Tech Stack
- **ESP32-CAM** – For capturing real-time images.
- **Edge Impulse** – For training and deploying a lightweight image classification model.
- **Python** – For data preprocessing, model evaluation, and optional visualization.
- **Arduino IDE** – For ESP32-CAM programming and model integration.

## 💡 Features
- Real-time ripeness classification on edge device.
- Lightweight ML model optimized for embedded deployment.
- Local web server interface (optional) for live preview and prediction display.
- Supports multiple fruit/vegetable types with custom dataset.

## 🚀 Getting Started
1. **Collect and label images** of different ripeness stages.
2. **Train model** on Edge Impulse (use MobileNet or FOMO).
3. **Deploy model to ESP32-CAM** (download as Arduino library).
4. **Flash code** using Arduino IDE with ESP32 board support.
