# 🧠 Customer Churn Prediction

![Customer Churn Banner](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*WZdoYPpmiIk1AcPQ1YHWug.png)

---

## 📌 Overview

**Customer churn prediction** helps businesses forecast which customers are likely to stop using their services or products. By identifying high-risk customers, businesses can take proactive steps to improve retention, offer personalized incentives, and enhance customer satisfaction.

In this project, we:
- Built a machine learning model to predict churn probability
- Identified key churn factor
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

EDA and Plots

Visualizing the categorical columns indicates:
1. About 83.2 % of the customers were retained, while 16.8% churned.

2. The company also has more male than female clients.

3. Most clients prefer logging in from their mobile phones to their phones and computers.

4. Most clients spend an average of 2 and 4 hours on the company’s app.

5. Most customers have about 3 or 4 devices registered for the retailer’s app.

6. Most customers prefer debit and credit cards to make payments.

7. City tier 2 has the lowest number of customers.

From the figure, notice that many customers placed their first and second orders, and the number reduced in subsequent orders. Additionally, the number of customers reduced a week after their last order.
![Customer Churn Banner](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*asou0LtTUdnX7ZIhmQ_VCQ.png)

We could use Hyperparamete Tuning or Feature enginnering methods to improve the accuracy further.

Feedback
If you have any feedback, please reach out at mr.abhi7208@gmail.com

🚀 About Me
Hi, I'm Abhishek! 👋
I am an AI Enthusiast and Data science & ML practitioner



## 🛠️ Tech Stack & Requirements

Install dependencies:
```bash
pip install -r requirements.txt

