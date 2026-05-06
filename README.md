# 📍 Indoor Localization System for Industrial Maintenance (WiSLAM-based)

## 📖 Overview
This project focuses on the design and prototyping of an indoor localization system aimed at guiding maintenance operators داخل industrial environments.

The system enables real-time positioning of a technician and provides navigation assistance toward faulty equipment, improving efficiency and reducing downtime.

## 🎯 Objectives
- Design a robust indoor positioning system without GPS
- Exploit existing Wi-Fi infrastructure (low-cost approach)
- Improve accuracy using hybrid sensor fusion
- Guide operators in real time داخل workshops

## 🧠 Key Concepts
- Wi-Fi Fingerprinting (RSSI / RTT)
- SLAM (Simultaneous Localization and Mapping)
- WiSLAM approach
- IMU / Pedestrian Dead Reckoning (PDR)
- Sensor Fusion (Wi-Fi + IMU + Vision)

## 🏗️ System Architecture
The system is composed of:
1. **Wi-Fi Localization Module**
   - RSSI or RTT-based positioning
2. **IMU Module**
   - Motion tracking (steps, direction)
3. **Fusion Algorithm**
   - Particle Filter / SLAM
4. **User Interface**
   - Navigation guidance (tablet or mobile)

## ⚙️ Methodology
- Literature review (state of the art)
- Selection of 2 localization approaches
- Prototype implementation
- Performance evaluation

## 📊 Evaluation Metrics
- Localization error (meters)
- Accuracy (%)
- Robustness to noise/interference
- Computational cost

## 🚀 Technologies
- Python / MATLAB
- Machine Learning (KNN, SVM, LSTM)
- Sensor data (Wi-Fi, IMU)
- SLAM algorithms

## 🧪 Experimentation
Tests are conducted in a controlled environment simulating an industrial workshop.

## 📈 Expected Results
- Meter-level accuracy
- Real-time tracking
- Improved navigation efficiency

## 🔮 Future Work
- Integration with Augmented Reality (AR)
- IoT connectivity
- Deployment in real industrial environments

## 👥 Team
- Rosilia MODJO  
- Nadia TCHUENTE  
- Joseph NKOULOU  

## 👨‍🏫 Supervisors
- Aloys NGUEPI  
- Humphrey OJONG  

## 📅 Academic Year
2025 – 2026

## 📌 Keywords
Indoor Localization, WiSLAM, Industry 4.0, Smart Maintenance, Sensor Fusion
