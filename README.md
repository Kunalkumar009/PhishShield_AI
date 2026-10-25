# 🛡️ PhishShield AI Platform

> **Explainable Malicious URL Risk Assessment using Ensemble Machine Learning**

PhishShield AI is an intelligent cybersecurity portal designed to detect, analyze, and explain phishing URLs in real time using Random Forest ensemble machine learning, structural telemetry parsing, and simulated global threat intelligence feeds.

---

## 🚀 Quick Start

### 1. Prerequisites
Make sure Python 3.9+ is installed on your system.

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the Application
```bash
streamlit run app.py
```
Or specify a custom port:
```bash
streamlit run app.py --server.port=8501
```

Once started, open your web browser at:
`http://localhost:8501`

---

## 🔐 Authentication Credentials

To access the security analyst portal:
- **Username / Security ID:** `admin`
- **Security Passcode:** `security123`

---

## 🛠️ Key Capabilities & Modules

1. **🛡️ Analyst Authentication Gateway**: Secure credential verification with intuitive form submission.
2. **📊 Executive Dashboard Overview**: Key operational KPIs (Model Accuracy, Precision, F1-Score, Ingestion count) and system architecture overview.
3. **🔍 Deep Packet AI Scanner Hub**:
   - Real-time extraction of structural URL features (Character Length, Subdomain Dots, Obfuscation `@` Symbol, HTTPS Transport Security).
   - Random Forest ensemble classification with probability-based Threat Risk Meter (0–100%).
   - Explainable AI breakdown highlighting why a specific URL was flagged.
   - One-click preset test links for easy verification.
4. **🌐 Global Threat Intelligence Feed**: Simulated API query against reputational cyber blocklists (OpenPhish, PhishTank, Spamhaus).
5. **📈 Threat Analytics Engine**: Interactive ledger inspection, statistical distributions, class distribution, and Random Forest **Feature Importance** rankings.
6. **📖 System Specifications**: Comprehensive architectural breakdown and runtime diagnostics.

---

## 📁 Project Structure

```
PhishShield_AI/
│
├── app.py                # Main Streamlit application and ML pipeline
├── urldata.csv           # Training dataset containing URL structural features and labels
├── requirements.txt      # Python package requirements
├── .gitignore            # Git exclusion rules
└── README.md             # Project documentation and guide
```

---

## 👨‍💻 Author
**Lead Analyst:** Kunal Kumar
