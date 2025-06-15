# 🚨 Disaster Recovery Alert UI

This is a simple frontend interface to trigger disaster recovery alerts using an AWS Lambda function. Once a message is submitted, it sends an SMS alert to a registered phone number using Amazon SNS.

---

## 🧠 What It Does

✅ Takes a message input (like "RDS crashed in us-east-1")  
✅ Sends it to an AWS Lambda function via API Gateway  
✅ The Lambda triggers an SMS notification via Amazon SNS  
✅ Displays confirmation on the screen

---

## 🌐 Live Demo (How to Test)

> This project is 100% frontend — no installations required.

1. Download the `index.html` file from this repository
2. Open it in your browser (double-click or right-click → open with browser)
3. Type your alert message
4. Click **Send Alert**
5. ✅ SMS will be received (if Phone number is configured in Lambda)

![UI Screenshot](https://github.com/Dhawan5/disaster-recovery-alert/blob/main/SMS%20message.jpg)

---

## 🛠 Built With

- HTML + JavaScript
- AWS Lambda
- Amazon API Gateway
- Amazon SNS



