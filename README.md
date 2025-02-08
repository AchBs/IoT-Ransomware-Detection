# 🔐 IoT Ransomware Detection Using AI

## 📌 Overview
With the rise of IoT devices, ransomware attacks targeting these systems are increasing. These attacks encrypt critical data and demand ransom, compromising smart cities, Industry 4.0, healthcare, and other sectors.  
This project presents an **AI-based solution** to detect and prevent ransomware in **Edge Computing environments** by analyzing **CPU and Disk usage patterns**.

## 🎯 Features
✅ **Real-time ransomware detection** based on anomaly detection  
✅ **Uses AI (Isolation Forest) to detect abnormal CPU & Disk behavior**  
✅ **Simulated IoT device activity for testing**  
✅ **Alert system when ransomware-like activity is detected**  

---

## ⚙️ How It Works
### 1️⃣ **Data Simulation**
- Simulated normal IoT device behavior (CPU and Disk usage)
- Introduced abnormal ransomware-like activity (sudden high CPU/Disk usage)

### 2️⃣ **AI Model**
- Trained using **Isolation Forest** (an unsupervised learning algorithm)
- Identifies anomalies based on learned normal behavior

### 3️⃣ **Detection & Alerting**
- When ransomware-like behavior is detected, an **alert is printed**
- Future work: **Automated response to block infected devices**

---

## 🛠️ Installation

### **1️⃣ Install Dependencies**
Ensure you have Python installed, then run:
```
pip install numpy pandas matplotlib scikit-learn
```
### **2️⃣ Clone the Repository**
```
git clone https://github.com/yourusername/IoT-Ransomware-Detection.git
cd IoT-Ransomware-Detection
```
### **3️⃣ Run the Detection Script**
```python detect_ransomware.py```

## 🖥️ Usage
- 1️⃣ Run the script to simulate IoT activity and ransomware detection
- 2️⃣ Monitor the output, where normal and abnormal behavior will be shown
- 3️⃣ Alert system will print a warning if ransomware-like activity is detected

## 📊 Example Output
```[INFO] Normal Activity: CPU: 30% | Disk: 40%
[INFO] Normal Activity: CPU: 32% | Disk: 38%
[INFO] Normal Activity: CPU: 31% | Disk: 42%
🚨 ALERT! Possible Ransomware Detected! 🚨
[WARNING] High CPU & Disk Usage: CPU: 95% | Disk: 97%
```

### 🛡️ Future Improvements
- 🚀 Enhancing AI Model: Use deep learning for better accuracy
- 🛡️ Automated Mitigation: Block infected devices on detection
- 📡 Edge Integration: Deploy on real Edge IoT devices

### 📬 Contact
- 👤 Achref Bensaad
- 📧 achref.bensaad@outlook.com
- 🐙 GitHub: AchBs
- 🚀 LinkedIn: [Achref Bensaad](https://www.linkedin.com/in/achref-bensaad/)
