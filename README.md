# AgroGuard – Crop Protection Using AI to Detect and Deter Animals

## 📌 Project Overview

AgroGuard is an AI-powered crop protection system designed to detect and deter wild animals from entering agricultural fields using real-time object detection. Leveraging the YOLO deep learning model, this system identifies animals from a camera feed and triggers alerts or deterrent mechanisms via an Arduino board.

It provides an efficient and cost-effective solution for reducing human-wildlife conflict and safeguarding farmlands near forest regions.

---

## 🔍 Problem Statement

Farmers living near forest borders face significant crop loss and safety risks due to frequent wild animal intrusions. Traditional methods like fences, scarecrows, or manual surveillance are ineffective, time-consuming, and lack species-specific response capabilities.

AgroGuard addresses this challenge through:
- Real-time animal detection
- Automated alert and deterrent responses
- Integration with Arduino for physical actions
- Optional GSM module for SMS alerts

---

## 💡 Key Features

- ✅ Real-time animal detection using YOLOv5
- ✅ Detects multiple wild animals (elephants, deer, tigers, etc.)
- ✅ Sends signals to Arduino for species-specific alerts
- ✅ Works in low-light and outdoor environments
- ✅ Reduces false alarms using delay timers and logic
- ✅ Expandable to include SMS alerts using GSM

---

## ⚙️ System Architecture

- **Camera Module**: Captures real-time video feed
- **YOLOv5 Model**: Detects and classifies animals
- **Serial Communication**: Sends detection info to Arduino
- **Arduino**: Triggers alarms, lights, or deterrents
- **Optional GSM Module**: Sends SMS alerts to farmers or officials

---

## 🛠️ Tech Stack

- **Frontend**: OpenCV for camera handling
- **Backend AI Model**: YOLOv5 (Ultralytics)
- **Embedded System**: Arduino Uno
- **Communication**: Serial (USB/COM), optional GSM for alerts
- **Programming Languages**: Python, C++

---

## 🚀 Getting Started

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/agroguard-ai-detection.git
    ```

2. Install Python dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Connect your Arduino and ensure the appropriate COM port is set in your Python code.

4. Run the detection script:
    ```bash
    python animal_detection.py
    ```

5. Load the model weights and let the system begin real-time detection.

---

## 🧠 Dataset & Model Training

- **Model**: YOLOv5 custom-trained on wild animal dataset
- **Classes**: Elephant, Deer, Bear, Tiger, Lion, etc.
- **Training Platform**: Google Colab using Ultralytics YOLOv5
- **Accuracy**: High-precision object classification for field use

---

## 📸 Sample Output

*Images or demo video can be inserted here to show detection in action.*

---

## 👨‍💻 Authors

- D.V. Rajkumar
- Kamil S
- Kirubasankar K
- **Mithin R C**

Department of Computer Science and Engineering  
Paavai Engineering College, Namakkal, India

---

## 📬 Contact

For queries or collaborations, please reach out at:  
📧 mithinchoodappa@gmail.com

---

## 📚 Reference

Published in the *International Journal of Scientific Research in Engineering and Management (IJSREM)*  
**DOI**: [10.55041/IJSREM45379](https://www.ijsrem.com/)

