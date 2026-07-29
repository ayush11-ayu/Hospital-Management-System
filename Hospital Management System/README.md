# 🏥 Hospital Management System | Salesforce Administrator Portfolio Project

![Salesforce](https://img.shields.io/badge/Salesforce-Administrator-blue?logo=salesforce)
![Platform](https://img.shields.io/badge/Platform-Salesforce%20Lightning-00A1E0)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Project Overview

The **Hospital Management System** is a Salesforce Administrator portfolio project built using **Salesforce Lightning Experience**. It demonstrates real-world Salesforce Administration skills by managing hospital operations such as patient registration, doctor management, appointment scheduling, medical records, billing, reporting, dashboards, automation, approval processes, and security.

This project showcases end-to-end Salesforce configuration without writing Apex code, following declarative development best practices.

---

# 🎯 Project Objectives

- Manage patient and doctor information
- Schedule and track appointments
- Maintain medical records
- Generate hospital billing
- Automate business processes
- Build reports and dashboards
- Implement security using roles, permission sets, and sharing settings
- Demonstrate Salesforce Administrator skills for recruiters

---

# 🛠 Salesforce Features Used

- Custom Objects
- Custom Fields
- Lookup Relationships
- Validation Rules
- Formula Fields
- Roll-Up Summary Fields
- Record-Triggered Flow
- Approval Process
- Reports
- Dashboards
- Lightning App Builder
- Page Layouts
- Custom Tabs
- Lightning App
- List Views
- Profiles
- Permission Sets
- Role Hierarchy
- Organization-Wide Defaults (OWD)
- Sharing Rules
- Public Groups

---

# 📁 Custom Objects

### Patient
Stores patient information.

Fields:
- Patient ID (Auto Number)
- Patient Name
- Age
- Gender
- Phone
- Email
- Blood Group
- Address
- Emergency Contact
- Insurance Number
- Admission Date
- Patient Status
- Adult or Minor (Formula Field)

---

### Doctor

Stores doctor details.

Fields:
- Doctor ID
- Doctor Name
- Department
- Specialization
- Experience
- Phone
- Email
- Consultation Fee
- Availability

---

### Appointment

Tracks appointments between patients and doctors.

Fields:
- Appointment ID
- Patient Lookup
- Doctor Lookup
- Appointment Date
- Appointment Time
- Appointment Status
- Reason for Visit
- Consultation Fee
- Room Number

---

### Medical Record

Stores patient diagnosis and treatment history.

Fields include:
- Medical Record ID
- Patient Lookup
- Diagnosis
- Prescription
- Treatment Notes

---

### Billing

Manages hospital billing information.

Fields include:
- Billing ID
- Patient Lookup
- Appointment Lookup
- Bill Date
- Total Amount
- Amount Paid
- Payment Method
- Payment Status

---

# 🔗 Object Relationships

Patient
↓
Appointments
↓
Doctors

Patient
↓
Medical Records

Patient
↓
Billing

Appointment
↓
Billing

---

# ✅ Validation Rules

### Appointment Date Validation

Prevents users from creating appointments in the past.

Business Rule:

- Appointment Date cannot be earlier than today's date.

---

# 🧮 Formula Fields

### Adult or Minor

Automatically categorizes patients.

Formula:

```text
IF(
Age__c >=18,
"Adult",
"Minor"
)
```

---

# ⚙ Automation

## Record-Triggered Flow

Automatically executes business logic when records are created or updated.

Examples:
- Appointment automation
- Billing automation

---

# ✔ Approval Process

Billing Approval Process

Workflow:

Billing Created

↓

Submit for Approval

↓

Manager Review

↓

Approved / Rejected

This demonstrates approval routing and record approval in Salesforce.

---

# 📊 Reports Created

- Patients by Blood Group
- Appointments by Status
- Completed Appointments
- Medical Records Summary
- Doctor Directory
- Billing Status Report

---

# 📈 Dashboards

Hospital Analytics Dashboard includes:

- Patients by Blood Group
- Appointment Status
- Billing Status
- Medical Records
- Doctor Summary

---

# 🔐 Security Configuration

Implemented:

- Role Hierarchy
- Hospital Manager Role
- Doctor Role
- Receptionist Role
- Permission Set
- Public Group
- Sharing Rules
- Organization-Wide Defaults

---

# 📋 List Views

Created custom list views including:

- Adult Patients

---

# 🎨 Lightning Experience

Configured:

- Hospital Management Lightning App
- Navigation Tabs
- Home Page
- Custom Page Layouts

---

# 📷 Project Screenshots

## Day 1 – Foundation
- Hospital App
- Patient Object
- Doctor Object

## Day 2 – Relationships
- Appointment Object
- Lookup Relationships
- Validation Rule

## Day 3 – Reports
- Patient Reports
- Appointment Reports

## Day 4 – Dashboard
- Hospital Dashboard
- Home Page

## Day 5 – Automation
- Flow Builder
- Automated Process

## Day 6 – Formula Fields
- Adult or Minor Formula
- Reports
- Dashboard

## Day 7 – Security
- Role Hierarchy
- Permission Set
- Public Group
- Sharing Rule

## Day 8 – Approval Process
- Billing Object
- Approval Process
- Approval History
- Approved Billing

## Day 9 – Reports & List Views
- Adult Patients List View
- Medical Records Report
- Dashboard Enhancements

## Day 10 – Final Project
- Final Dashboard
- Final Home Page
- Project Completion

---

# 📂 Project Structure

```
Hospital-Management-System/
│
├── README.md
├── LICENSE
├── .gitignore
│
└── screenshots/
    ├── Day1/
    ├── Day2/
    ├── Day3/
    ├── Day4/
    ├── Day5/
    ├── Day6/
    ├── Day7/
    ├── Day8/
    ├── Day9/
    └── Day10/
```

---

# 🚀 Skills Demonstrated

- Salesforce Administration
- CRM Configuration
- Custom Object Design
- Relationship Management
- Automation with Flow
- Validation Rules
- Formula Fields
- Approval Process
- Reports & Dashboards
- Lightning Experience
- Security & Sharing
- Data Management
- Page Layout Customization

---

# 💼 Suitable For

This project demonstrates practical Salesforce Administrator skills and can be included in:

- Resume
- GitHub Portfolio
- LinkedIn Projects
- Salesforce Administrator Interviews

---

# 👨‍💻 Author

**Ayush Mehunkar**

GitHub:
GitHub: https://github.com/ayush11-ayu

---

