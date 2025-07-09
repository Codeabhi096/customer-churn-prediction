# 🧠 Customer Churn Prediction

![Customer Churn Banner](./bd6104bd-85a3-4311-8feb-263f874b5731.png)

---

## 📌 Overview

**Customer churn prediction** helps businesses forecast which customers are likely to stop using their services or products. By identifying high-risk customers, businesses can take proactive steps to improve retention, offer personalized incentives, and enhance customer satisfaction.

In this project, we:
- Built a machine learning model to predict churn probability
- Identified key churn factors
- Designed a Flask web app for live predictions
- Used various visualization techniques to analyze user behavior

---

## 🤔 Why Predict Customer Churn?

Retaining a customer is often cheaper than acquiring a new one. For subscription-based or repeat-client businesses (like ISPs or e-commerce), churn means loss of potential future revenue.

Example:
> A telecom or internet provider invests in technicians and hardware to onboard a customer. If that customer churns after a month, it becomes a financial loss. Therefore, **early churn detection = saved revenue.**

---

## 📊 Case Study: E-Commerce Churn

An e-commerce company wants to launch targeted marketing campaigns. To do so, they use historical user data (logins, payments, satisfaction score, etc.) to:
- Predict churn probability
- Discover usage patterns
- Retain high-risk users using personalized strategies

---

## 📁 Dataset

- Provided by **DataMites Institute**
- Format: `.xlsx`
- Contains: 
  - Login behavior
  - Device and payment preferences
  - Gender, marital status
  - Number of registered devices
  - Complaint and satisfaction metrics
  - Churn label (1 = left, 0 = retained)

✅ **No duplicate rows**  
🧹 `CustomerID` column removed (not predictive)

---

## 📈 EDA and Visual Insights

Below are a few major findings from the exploratory data analysis:

![EDA Charts](./b4df12ff-6f3f-4bcc-8272-d257ae083115.png)

### Key Observations:
- **83.2%** of users stayed, while **16.8% churned**
- More **males** than females in user base
- Most users prefer using the app on **mobile phones**
- Majority spend between **2–4 hours** daily on the app
- **Tier-2 cities** have the lowest customer base
- Debit and credit cards are the most preferred payment methods

---

## 🛠️ Tech Stack & Requirements

Install dependencies:
```bash
pip install -r requirements.txt

