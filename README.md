# 🚀 User Behavior Analytics (UBA) using Machine Learning

## 📌 Overview
This project detects **anomalous user behavior** from network logs using 
time-based analysis and unsupervised machine learning.

It identifies suspicious users such as:
- Bots 🤖
- Scanners 🔍
- Attackers 🚨

---

## 🧠 Concept

User Behavior Analytics (UBA) analyzes how users interact with systems 
and detects abnormal patterns.

👉 Normal users behave similarly  
👉 Attackers behave differently  

We use **Isolation Forest** to detect anomalies.

---

## 📊 Features Used

- Total Activity (number of requests)
- Unique Sites visited
- Average Time Gap between requests
- Time Variance

---

## ⚙️ Tech Stack

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 🚀 How It Works

1. Load dataset
2. Simulate timestamps
3. Create behavioral features
4. Train anomaly detection model
5. Visualize suspicious users

---

## 📈 Output

- Detects abnormal users
- Visualizes behavior patterns
- Highlights anomalies

---

## 🏆 Use Cases

- Cybersecurity
- Fraud detection
- Bot detection
- Network monitoring

---

## ▶️ Run the Project
## 📸 Sample Output

Graph showing anomaly detection based on user behavior patterns.
```bash
pip install -r requirements.txt
python src/uba_model.py
