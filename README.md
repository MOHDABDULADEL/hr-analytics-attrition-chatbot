# 🧠 HR Analytics Dashboard – Attrition, Engagement & AI Chatbot

![Status](https://img.shields.io/badge/Project-Active-brightgreen)
![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Streamlit](https://img.shields.io/badge/Framework-Streamlit-ff4b4b)
![Machine Learning](https://img.shields.io/badge/ML-Attrition%20Prediction-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 🚀 Project Overview

This project is an **end-to-end HR Analytics system** that combines:

- 📊 **Attrition & engagement analytics dashboard**
- 🤖 **ChatGPT-powered HR assistant**
- 🔍 **Employee profile & risk insights**
- 🧮 **Attrition prediction ML model**
- 🗄️ **SQLite database integration**
- 📈 **Power BI-style charts**

It helps HR teams:

- understand **who is likely to leave**
- measure **employee engagement**
- get **AI-generated insights**
- view **risk recommendations per employee**

---

## 🛠️ Tech Stack

### 🚨 Core Technologies
| Tool | Description |
|------|-------------|
| 🐍 Python | Programming language |
| 🎈 Streamlit | Interactive web app framework |
| 🤖 OpenAI GPT | Chatbot HR assistant |
| 🧠 Scikit-Learn | Machine learning model |
| 🗄️ SQLite | Relational database |
| 📊 Altair | Visual analytics charts |
| 📦 Pandas / Numpy | Data processing |

---

## ⭐ Key Features

✔ HR AI chatbot assistant  
✔ Attrition prediction model  
✔ Employee engagement metrics  
✔ Employee profile & risk panel  
✔ SQL database connectivity  
✔ Power BI-style visual analytics  
✔ Modern responsive UI  
✔ Download-ready screenshots  
✔ Works fully offline (except chatbot)

---

## 🧩 Machine Learning Component

Model predicts:

- probability of attrition
- predicted attrition label (Yes/No)

Features used include:

- age  
- years at company  
- monthly income  
- working years  
- engagement score  
- work-life balance  
- satisfaction metrics  

---

## 🗄️ Database

Backend uses:

```
SQLite Database: hr_analytics.db
Table: employee_hr
```

Columns include:

- EmployeeNumber
- Department
- JobRole
- Attrition
- EngagementLevel
- EngagementScore
- Satisfaction metrics

---

## 🤖 Chatbot Integration

Chatbot uses:

- **OpenAI API**
- conversational memory
- context-aware HR responses

Capabilities:

- policy Q&A
- attrition reasoning
- engagement improvement ideas
- SQL-style data questions

---

## 🖥️ Screenshots

> Add your screenshots in a folder named `/screenshots`

```
/screenshots/dashboard_overview.png
/screenshots/chatgpt_hr_chatbot.png
/screenshots/attrition_prediction_tool.png
/screenshots/employee_profile_risk.png
```

### 🔹 Dashboard Overview
![Dashboard](screenshots/dashboard_overview.png)

### 🔹 HR Chatbot
![Chatbot](screenshots/chatgpt_hr_chatbot.png)

### 🔹 Attrition Prediction Tool
![Predictor](screenshots/attrition_prediction_tool.png)

### 🔹 Employee Profile & Risk
![Employee Profile](screenshots/employee_profile_risk.png)

---

## 🧭 How to Run Locally

### 1️⃣ Clone repository

```bash
git clone <your-repo-url>
cd <repo-folder>
```

### 2️⃣ Create virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Set OpenAI API key

Windows CMD:

```bash
setx OPENAI_API_KEY "your_key_here"
```

Mac/Linux:

```bash
export OPENAI_API_KEY="your_key_here"
```

### 5️⃣ Run the application

```bash
streamlit run chatbot_app.py
```

---

## 📚 Dataset Reference

Dataset: **HR Analytics – Employee Attrition & Performance**

Source options:

- Kaggle HR Analytics Datasets
- IBM HR Analytics Attrition Dataset
- Self-generated engagement features

---

## 🏗️ Future Enhancements

- PDF report generation  
- SHAP explainability  
- Role-based login  
- Admin monitoring panel  
- Resume parser for HR  

---

## 👤 Author

**Tonumay Bhattacharya**

- 📧 Email: add if you wish  
- 💼 Portfolio: add if you wish  
- 🐙 GitHub: your profile link  
- 🔗 LinkedIn: your profile link  

---

## 🏁 License

This project is licensed under the **MIT License**.

