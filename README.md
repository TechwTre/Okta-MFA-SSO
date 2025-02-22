
# Okta SSO & MFA Lab

## 📌 Project Overview
This lab demonstrates how to set up **Okta Single Sign-On (SSO) and Multi-Factor Authentication (MFA)** with **adaptive MFA policies** and **API-based user lifecycle automation**. Additionally, it includes **PowerShell scripts** for user provisioning and **simulated IAM governance workflows** with logging & alerting.

## 🚀 Features
- 🔐 **Okta SSO & MFA Implementation**
- ⚡ **Adaptive MFA Policies**
- 🛠 **API-Based User Lifecycle Automation**
- 🏗 **PowerShell Automation for User Management**
- 📜 **IAM Governance Logging & Alerting**

---

## 🛠 Prerequisites
- [ ] Okta Developer Account ([Sign up for free](https://developer.okta.com/))
- [ ] Python 3.x installed
- [ ] PowerShell (for Windows automation scripts)
- [ ] Okta API Token (Generated in Okta Admin Console)
- [ ] A test application for SSO configuration

---

## 📂 Project Structure
```
📂 okta-sso-mfa-lab
│── 📜 README.md       # Documentation
│── 📜 .env.example    # Sample environment config
│── 📜 requirements.txt # Python dependencies
│── 🐍 setup_okta_sso.py  # Script to configure SSO & MFA in Okta
│── 📜 user_lifecycle.ps1 # PowerShell script for user provisioning/deprovisioning
│── 📜 alert_logging.py  # IAM Governance logging & alerting
```

---

## 🔧 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourgithubusername/okta-sso-mfa-lab.git
cd okta-sso-mfa-lab
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Configure Environment Variables
Create a `.env` file in the project root and add:
```
OKTA_ORG_URL=https://your-okta-domain.okta.com
OKTA_API_TOKEN=your_api_token
```

### 4️⃣ Run the Okta SSO & MFA Setup
```bash
python setup_okta_sso.py
```

---

## 🔑 Key Components

### `setup_okta_sso.py` (Python)
Handles:
✅ **Creating an Okta Application for SSO**
✅ **Enabling MFA Policies (Adaptive MFA, TOTP, etc.)**
✅ **Assigning users/groups to the app**

### `user_lifecycle.ps1` (PowerShell)
Handles:
✅ **Automated user provisioning & deprovisioning**
✅ **Role-based access management**

### `alert_logging.py` (Python)
Handles:
✅ **Logging IAM events (provisioning, MFA attempts, etc.)**
✅ **Sending email alerts on critical security events**

---

## 🔥 Running IAM Governance & Automation
### Execute User Lifecycle Management Script
```powershell
./user_lifecycle.ps1
```

### Start IAM Logging & Alerting
```bash
python alert_logging.py
```

---

## 📌 Next Steps
🔹 Deploy this setup in a real-world IAM lab.  
🔹 Extend with additional Okta Workflows or SCIM provisioning.

---

## 📜 License
This project is open-source and available for educational use.

---
### ⭐ Show Some Love
If this project helps you, star it on GitHub! ⭐
