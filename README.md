# 🚀 Secure Healthcare Data Delivery using AWS SNS in a Private VPC

## 📌 Project Overview
This project focuses on the **healthcare domain**, where patient reports must be shared securely and privately.  
The solution uses **AWS CloudFormation** to build a private VPC, deploys an application on **EC2**, and leverages **Amazon SNS** for private, secure message delivery to patients’ mobile devices.  

---

## 🛠️ Tools & Technologies
- **Cloud Services:** AWS CloudFormation, VPC, EC2, SNS  
- **Scripting:** Python (for SNS publish)  
- **Security:** Private messaging within VPC  

---

## ⚙️ Architecture
![Architecture Diagram](screenshots/architecture.png)  
*(Replace with your Healthcare SNS architecture diagram)*  

---

## 🚀 Implementation Steps
1. **VPC Creation**
   - Used **AWS CloudFormation** to create a secure, isolated **VPC**.  
   - Launched an **EC2 instance** inside the VPC to host the report publishing app.  

2. **SNS Configuration**
   - Created an **Amazon SNS Topic** for patient notifications.  
   - Configured **private message publishing**, restricting delivery to authorized subscribers only.  

3. **App Deployment**
   - Hosted a reporting service on **EC2 instance** inside the VPC.  
   - Integrated the app with **SNS API** to publish private messages.  

4. **Testing**
   - Subscribed devices to the SNS topic.  
   - Verified **secure delivery** of patient report notifications.  

