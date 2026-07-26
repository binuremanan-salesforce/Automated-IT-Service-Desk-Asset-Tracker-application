# 👥 User Experience & Security

A good application should not only automate business processes but also provide a simple user experience while protecting sensitive data. In this project, I focused on making the application easy to use for employees and technicians, while ensuring users only have access to the information they need.

---

# 🎨 User Experience

To create a user-friendly application, I customised the Lightning interface using several Salesforce features.

## 📝 Lightning Record Pages

I created custom Lightning Record Pages for the main objects to display the most important information in a clear and organised layout. This makes it easier for users to view and update records without searching through unnecessary fields.

**Business Benefit:**
- Improves navigation.
- Displays relevant information clearly.
- Reduces the time required to update records.

---
Service Request record page
<img width="1328" height="558" alt="image" src="https://github.com/user-attachments/assets/1e79800e-d9f4-4d8b-b33b-b795a7c9c424" />

## 📋 Dynamic Forms

I used Dynamic Forms to display fields based on the current stage of a Service Request. Users only see the information that is relevant +
3to them, making the page cleaner and easier to understand.

**Business Benefit:**
- Reduces page clutter.
- Makes record pages easier to use.
- Improves the overall user experience.

---

## ⚡ Dynamic Actions

Dynamic Actions were added to display actions only when they are needed. For example, technicians only see actions that are relevant to the current status of a Service Request.

<img width="1349" height="558" alt="image" src="https://github.com/user-attachments/assets/94ab21d1-e4a1-41ab-9baf-baaf1ce4af95" />

**Business Benefit:**
- Simplifies the user interface.
- Reduces unnecessary actions.
- Guides users through the support process.

---

## 🚦 Path Component

I added a Path Component to the Service Request record page so users can easily track the progress of a ticket from **New** to **Closed**. The Path highlights the current status and helps users understand the next step in the support process.

**Business Benefit:**
- Provides a clear visual representation of the ticket lifecycle.
- Encourages consistent business processes.
- Helps users update records correctly.

<img width="1289" height="539" alt="image" src="https://github.com/user-attachments/assets/46d6acf7-c234-443d-bb25-5a49ea4c222b" />

---

## 🚀 Quick Actions

Quick Actions allow users to perform common tasks directly from the record page without navigating to different screens. This makes updating service requests faster and improves productivity.

**Business Benefit:**
- Saves time.
- Reduces the number of clicks.
- Improves efficiency for technicians.

---

# 🔒 Security

Security is an important part of every Salesforce application. I configured access controls to ensure users only have access to the records and features required for their role.

---

## 👤 Profiles

Profiles were used to control the basic permissions for different types of users, including Employees, Technicians, and Managers. This determines what users can view, create, edit, and delete.

**Business Benefit:**
- Controls access to Salesforce features.
- Ensures users have the correct level of access.

---

## 🔑 Permission Sets

Permission Sets were created to provide additional permissions without modifying user profiles. This makes it easier to grant extra access when required.

**Business Benefit:**
- Provides flexible access management.
- Follows Salesforce best practices.
- Reduces the need for multiple profiles.

---

## 🏢 Role Hierarchy

A Role Hierarchy was configured to reflect the organisation's reporting structure. Managers can view records owned by their team members, while employees only have access to their own records.


**Business Benefit:**
- Supports management reporting.
- Provides controlled record visibility.
- Mirrors a real business structure.

<img width="1097" height="507" alt="image" src="https://github.com/user-attachments/assets/1e8f4573-832d-4169-a80f-087da2cb741c" />

---

## 🤝 Sharing Rules

Sharing Rules were used to extend record access where required. For example, technicians can access Service Requests assigned to them, allowing them to update ticket status and resolution details.

**Business Benefit:**
- Enables collaboration.
- Maintains data security.
- Ensures users only access relevant records.
<img width="1331" height="490" alt="image" src="https://github.com/user-attachments/assets/d4192472-7e5b-4521-a0f0-6d3966a32842" />

---

# ✅ Summary

This project combines a user-friendly interface with a secure data model. By using Lightning Record Pages, Dynamic Forms, Dynamic Actions, Path, and Quick Actions, I created an application that is simple to use and improves productivity. At the same time, Profiles, Permission Sets, Role Hierarchy, and Sharing Rules ensure that users have the appropriate level of access while keeping business data secure.

These features demonstrate my understanding of both the user experience and security capabilities available to a Salesforce Administrator.
