# Salesforce Project - SmartBridge Capstone Project: AgriEdge Order Management System (OMS)
Revolutionizing Agriculture with AgriEdge Order-Manage Ltd: A Salesforce-Driven Order Management Solution

This repository contains the metadata and source code for the **AgriEdge Or-Mange Ltd** Salesforce application, developed in a Salesforce Developer Org.

## 📌 Overview
- **Purpose:** To simplify AgriEdge Or-Mange Ltd's order management operations, powered by Salesforce. Order processing is automated to minimize human mistakes, real-time inventory is offered for precise stock control, and seamless integration with customer support channels guarantees timely, knowledgeable assistance. The OMS provides the business with reporting and analystics, enabling it to make data-driven choices, maximize supply chain efficiency, and keep a competitive advantage in the food production and agriculture sector.
- **Technologies:** Apex, Triggers, Custom Objects
- **Platform:** Salesforce

## 🛠 Prerequisites
Before using this repository, you will need:
- Salesforce CLI ([Install here](https://developer.salesforce.com/tools/sfdxcli))
- A Salesforce Developer Org ([Sign up here](https://developer.salesforce.com/signup))
- Visual Studio Code (recommended) with the Salesforce Extensions Pack

## 📥 Retrieve the Source
To retrieve this source into your own org:
```bash
sf org login web --set-alias MyDevOrg
sf project deploy start --target-org MyDevOrg
```

## 📂 Project Structure
- force-app/main/default/classes → Apex Classes
- force-app/main/default/triggers → Apex Triggers
- force-app/main/default/lwc → Lightning Web Components
- manifest/package.xml → Metadata manifest file

## 🚀 Deployment
1. Clone this repository:
   ```
   git clone [https://github.com/yourusername/your-repo-name.git](https://github.com/Pal-C/SmartBridge-CapstoneProject.git)
   cd your-repo-name
   ```
2. Authorize your Salesforce org:
   ```
   sf org login web --set-alias MyDevOrg
   ```
3. Deploy to the org:
   ```
   sf project deploy start --target-org MyDevOrg
   ```
   
## 📄 Notes
- This project was created in a Salesforce Developer Org for the Smartbridge Internship.
- Metadata was retrieved using the Salesforce CLI.
