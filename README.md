# Automated IT Service Desk & Asset Tracker

## 📌 Project Overview

As part of my Salesforce Administrator learning, I wanted to build a project that reflects a real business scenario rather than just completing Trailhead exercises. That's why I developed the Automated IT Service Desk & Asset Tracker using a Salesforce Developer Edition.

The application helps an organisation manage its IT assets and employee support requests in one place. Employees can raise service requests for issues such as hardware problems, software installation, network connectivity, or access requests. Each request is linked to the employee and, where applicable, the IT asset they are using.

To reduce manual work, I implemented several automations using Salesforce Flow. When a service request is created, the system automatically assigns a technician, calculates the SLA due date based on the ticket priority, and sends email notifications to keep everyone informed. I also created a scheduled flow that checks for overdue requests each day and sends reminder emails to technicians so that important tickets are not missed.

To make the application secure, I configured roles, permission sets, and sharing rules so users only have access to the records they need. I also built reports and dashboards that allow managers to monitor open tickets, technician workload, SLA compliance, and IT asset allocation.

The entire application was built using Salesforce's declarative tools without writing Apex code. Through this project, I gained hands-on experience with custom objects, relationships, validation rules, formula fields, Flows, Lightning App Builder, reports, dashboards, and security configuration. It has been a great way to apply my Salesforce knowledge in a practical project, and it demonstrates the skills I can bring to a Salesforce Administrator role

* **Role:** Salesforce Administrator (Solo Project)
* **Environment:** Free Developer Edition Org

## 💼 The Business Problem
 I chose to build this project because many organisations still struggle with managing IT support requests and company assets efficiently. In a typical workplace, employees often report IT issues through emails, phone calls, or spreadsheets. This makes it difficult to track requests, assign them to the right technician, monitor progress, and ensure issues are resolved on time. Important requests can easily be missed, and managers have very little visibility into the team's workload or SLA performance.

Another common challenge is asset management. Without a central system, it's hard to know which employee has been assigned a particular laptop, desktop, or other IT equipment, making it difficult to manage inventory and warranty information.

I designed this Salesforce application to solve these problems by bringing everything into one place. Employees can easily log support requests, technicians can track and update their assigned tickets, and managers can monitor performance through reports and dashboards. By automating tasks such as technician assignment, SLA calculations, and email notifications, the system reduces manual effort, improves response times, and helps the IT team deliver a more organised and efficient support service.

This version sounds like you're explaining the business problem you identified and how your solution addresses it, which is exactly what interviewers and recruiters want to hear.

## 🛠️ The Solution

To solve these challenges, I built a custom Salesforce application using declarative tools. The solution centralises IT support requests and asset management while automating repetitive tasks to improve efficiency and data accuracy.

 ## Custom Data Model

I designed a custom data model using four main objects: Employee, IT Asset, Technician, and Service Request. These objects are connected using Lookup relationships, allowing each service request to be linked to the employee who raised it, the assigned IT asset, and the technician responsible for resolving the issue. This structure provides a clear and organised way to manage support requests and company assets.

 ## Process Automation

I used Salesforce Flow to automate key business processes. When a new service request is created, the system automatically assigns a technician, calculates the SLA due date based on the ticket priority, and sends email notifications to both the employee and technician. I also built a scheduled flow that runs daily to identify overdue service requests and send reminder emails, helping the IT team meet SLA targets without manual follow-up.

 ## Data Quality

To maintain accurate and reliable data, I implemented validation rules, required fields, and formula fields. These prevent incomplete or incorrect information from being saved, ensure mandatory details are provided when creating service requests, and automatically calculate values such as ticket age and SLA status. I also customised page layouts and Dynamic Forms so users only see fields relevant to their role and the current stage of the support process.

 ## Security

I configured roles, permission sets, profiles, and sharing rules to ensure users only have access to the records and features appropriate for their role. Employees can view and manage their own service requests, technicians can update the tickets assigned to them, and managers have broader visibility through reports and dashboards.

 ## Reporting and Dashboards

I created custom reports and dashboards to provide real-time insights into IT operations, including open and closed tickets, technician workload, SLA compliance, and IT asset allocation. These dashboards help managers monitor team performance and identify areas that need attention.

This project allowed me to apply core Salesforce Administrator concepts in a practical business scenario and demonstrates my ability to design, automate, secure, and maintain a complete Salesforce solution using declarative tools.

## 📸 System Walkthrough & Visuals
Home Tab
<img width="1329" height="565" alt="image" src="https://github.com/user-attachments/assets/5e8b0cfa-bad3-4d78-9a68-7ec8f3026ad1" />

### 2. Automation (Flow Builder)

<img width="1095" height="541" alt="image" src="https://github.com/user-attachments/assets/8ea49d72-b4ca-4eb0-9ad7-51593ccb033c" />


### 3. User Experience & Security
![Lightning Page Screenshot](link-to-your-image.png)
*Show your Dynamic Forms or how you used Permission Sets to hide fields.*

### 4. Analytics & Insights
![Dashboard Screenshot](link-to-your-image.png)
*Show the dashboard you built for management.*

## 🚀 Key Business Impact
What are the results of your work? (Use realistic metrics).
* **Efficiency:** Cut lead conversion time by 30% via automated tasks.
* **Data Accuracy:** Stopped missing phone numbers using validation rules.
