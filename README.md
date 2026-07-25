# ⚙️ Automation

To make the IT Service Desk more efficient, I used **Salesforce Flow** to automate several business processes. These automations reduce manual work, improve data consistency, and ensure support requests are handled quickly and accurately.

---

<img width="1007" height="573" alt="image" src="https://github.com/user-attachments/assets/1dd3d287-c3fa-4de8-8c23-002319008d02" />

## 👨‍💻 Automatic Technician Assignment

When a new Service Request is created, the system automatically assigns a technician. This eliminates the need for manual assignment and ensures that every request is allocated to the appropriate technician as soon as it is logged.

**Business Benefit:**
- Reduces manual effort.
- Ensures requests are assigned immediately.
- Improves response times.

---
<img width="1180" height="523" alt="image" src="https://github.com/user-attachments/assets/956e434c-51b2-4baf-aec4-dfad7a7b278a" />

## 📅 Automatic SLA Due Date Calculation

The SLA Due Date is calculated automatically based on the priority of the service request. For example, Critical and High priority requests receive shorter response times than Medium or Low priority requests.

**Business Benefit:**
- Standardises SLA calculations.
- Helps technicians prioritise their work.
- Supports SLA compliance.

---
<img width="702" height="514" alt="image" src="https://github.com/user-attachments/assets/e922826f-7fe0-4bd8-a0b6-58997019f7e0" />

## 📧 Automated Email Notifications

When a Service Request is created, the system automatically sends email notifications. The assigned technician receives the details of the new ticket, while the employee receives a confirmation that their request has been successfully submitted.

**Business Benefit:**
- Keeps everyone informed.
- Reduces manual communication.
- Improves the overall support experience.

---
<img width="717" height="519" alt="image" src="https://github.com/user-attachments/assets/e5403984-2f01-41db-9008-2d026384df10" />

## ⏰ Scheduled Flow – Daily SLA Reminder

I created a **Scheduled Flow** that runs automatically every day to check for service requests that have exceeded their SLA Due Date and are still open. If any overdue requests are found, the flow sends reminder emails to the assigned technicians, helping them prioritise unresolved tickets before they become a bigger issue.

**Business Benefit:**
- Automatically monitors overdue service requests.
- Helps technicians stay on top of pending work.
- Improves SLA compliance and service delivery.
- Eliminates the need for manual follow-up.

---
<img width="567" height="500" alt="image" src="https://github.com/user-attachments/assets/d21fd351-a137-4662-96d9-6215fcb02114" />


## 🖥️ Screen Flow – Guided Service Request Creation

To make it easier for employees to submit IT support requests, I built a **Screen Flow** that provides a simple, step-by-step process for creating a new Service Request. Instead of using the standard Salesforce record page, users are guided through the required information, making the process more user-friendly and reducing data entry errors.

The Screen Flow captures information such as the employee, issue details, priority, category, and related IT asset before automatically creating the Service Request.

**Business Benefit:**
- Provides a simple and intuitive user experience.
- Ensures all required information is collected.
- Reduces incomplete or inaccurate service requests.
- Demonstrates how Screen Flows can be used to build guided business processes.

---

## 🚀 Summary

All automation in this project was built using Salesforce's declarative tools, without writing Apex code. By using **Record-Triggered Flows**, **Scheduled Flows**, and a **Screen Flow**, I was able to automate key business processes, improve data accuracy, reduce manual effort, and create a more efficient IT Service Desk application.
