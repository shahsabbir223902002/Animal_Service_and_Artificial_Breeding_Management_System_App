# Amratali Artificial Breeding & Animal Service App
**Digitalizing Animal Service & Artificial Breeding Management**
> Simple • Reliable • Offline-First • Field Friendly

Rabby Animals Official is a native Android field-service management application designed for **Md. Shah Walimullah Rabby**, Government AI Technician.

The application helps manage animal owners, livestock profiles, veterinary treatment records, artificial insemination (AI), pregnancy follow-ups, vaccination, deworming, appointments, reminders, reports, and professional contact information.

---

## 📱 Project Overview

The main goal of this application is to replace manual and fragmented animal-service records with a simple, searchable, and user-friendly digital system.

The application is designed especially for **field-service work**, where internet connectivity may sometimes be unavailable.

### 👨‍⚕️ Primary User

**Md. Shah Walimullah Rabby**  
Government AI Technician  
**Amratali Artificial Breeding Center**  
Upazila Prani Sampad Doptor & Veterinary Hospital  
Adarsha Sadar, Cumilla, Bangladesh

📞 **Mobile:** 01845-233917

---

# 🎯 Project Objectives

- Digitize animal-owner information.
- Maintain complete livestock profiles.
- Store animal treatment history.
- Manage Artificial Insemination (AI) records.
- Track pregnancy follow-ups.
- Manage vaccination schedules.
- Manage deworming records.
- Manage field appointments.
- Provide treatment history by month/date range.
- Generate PDF and CSV reports.
- Provide quick access to Rabby's professional contact information.
- Support offline field operations.
- Provide a foundation for future cloud synchronization and multi-user support.

---

# ✨ Key Features

## 🔐 1. Authentication & Profile Lock

- Secure login screen.
- Remember Login option.
- PIN-based access.
- Change PIN from Settings.
- Logout / Lock application.
- Profile-based authentication.

> **Important:** The default/demo PIN should be changed before production deployment.

---

## 📊 2. Dashboard

The dashboard provides a quick overview of daily animal-service activities.

### Live Statistics

- Total Owners
- Total Animals
- Today's Visits
- Pending Follow-ups
- AI Cases
- Pregnancy Checks Due
- Vaccines Due
- Deworming Due

### Quick Actions

- ➕ Add Owner
- 🐄 Add Animal
- 🩺 Add Visit
- 🐂 Add AI Record
- 📅 Add Appointment

### Dashboard Sections

- Today's Schedule
- Recent Activities
- Treatment Insights
- Upcoming Follow-ups

---

# 👨‍🌾 3. Owner Management

Each animal owner has a dedicated profile.

### Owner Information

- Owner Code
- Owner Name
- Primary Mobile Number
- Alternative Phone Number
- Village
- Union
- Upazila
- District
- Full Address
- NID / Owner ID
- GPS Coordinates
- Notes

### Owner Actions

📞 Call  
💬 SMS  
📍 Open Map  
🐄 Add Animal  
🩺 Add Visit

### Search Owners By

- Name
- Mobile Number
- Owner Code
- Village

---

# 🐄 4. Animal & Livestock Management

Each owner can have multiple animals.

### Supported Species

- Cow
- Goat
- Buffalo
- Other

### Animal Information

- Animal ID / Tag Number
- Animal Name
- Species
- Breed
- Age
- Weight
- Color
- Health Status
- Pregnancy Status
- Owner
- Animal Photo
- Notes

### Animal History

Each animal maintains a chronological record of:

- 🩺 Medical Treatment
- 🐂 Artificial Insemination
- 💉 Vaccination
- 💊 Deworming
- 📅 Appointments
- 🔔 Follow-ups

---

# 🩺 5. Veterinary Treatment Management

The treatment module stores complete case information.

### Treatment Record

- Treatment ID
- Date
- Time
- Owner
- Animal
- Main Problem
- Symptoms
- Examination Findings
- Diagnosis / Observation
- Treatment Given
- Medicine Information
- Farmer Advice
- Follow-up Date
- Notes
- Photos/Documents

Every treatment automatically becomes part of the animal's medical/service history.

> This application is a record-management tool. It should not independently diagnose diseases or generate medical prescriptions.

---

# 📅 6. Advanced Treatment History

One of the major features of the application is the advanced treatment-history system.

Rabby can quickly find previous treatment records.

### Date Filters

- Today
- This Week
- This Month
- Last Month
- Last 2 Months
- Last 3 Months
- Last 6 Months
- This Year
- Custom Date Range

### Example

Rabby can search:

> How many animals were treated last month?

or

> Show all animals treated during the last 3 months.

or

> How many cows were treated in August?

---

# 📈 7. Monthly Treatment Analytics

The application provides treatment statistics based on selected periods.

### Monthly Summary

- Total Animals Treated
- Total Treatment Visits
- Total Owners Served
- Cow Treatments
- Goat Treatments
- Buffalo Treatments
- Other Animal Treatments
- Completed Follow-ups
- Pending Follow-ups

### Example

```text
September 2026

Total Animals Treated: 47
Total Treatment Visits: 58
Total Owners Served: 39

Cow: 35
Goat: 10
Buffalo: 2

Pending Follow-ups: 6
```

---

# 🔎 8. Treatment Search

Treatment records can be searched using:

- Owner Name
- Mobile Number
- Animal ID
- Animal Name/Tag
- Village
- Treatment ID
- Treatment Problem
- Date
- Month

Multiple filters can be combined.

Example:

```text
Date:
Last 3 Months

Animal:
Cow

Village:
Amratali
```

The application will show matching treatment records.

---

# 🐂 9. Artificial Insemination (AI) Management

AI Management is one of the core modules because the application is designed for a Government AI Technician.

### AI Record

- AI Record ID
- Owner
- Animal
- AI Date
- Heat/Estrus Detection Date
- Bull/Semen Information
- Semen Station
- Target Breed
- Technician
- Notes
- Pregnancy Check Date
- Pregnancy Result
- Expected Calving Date
- Follow-up Date

### AI Status

- Scheduled
- AI Completed
- Pregnancy Check Pending
- Confirmed Pregnant
- Not Pregnant
- Follow-up Required
- Completed

---

# 🤰 10. Pregnancy Tracking

Pregnancy records include:

- Animal
- Owner
- AI Date
- Pregnancy Check Date
- Pregnancy Result
- Expected Calving Date
- Actual Calving Date
- Notes

### Status

- Pending
- Pregnant
- Not Pregnant
- Calved

The current application uses target scheduling values of:

- **60 days after AI → Pregnancy Check**
- **280 days after AI → Expected Calving**

These values should be configurable and verified against applicable professional/operational guidance before production use.

---

# 💉 11. Vaccination Management

The application supports vaccination tracking.

### Example Vaccines

- FMD
- Anthrax
- Black Quarter
- PPR

### Vaccination Record

- Animal
- Owner
- Vaccine Name
- Date Given
- Next Due Date
- Dose Information
- Notes

The dashboard can display:

- Vaccination Due Today
- Vaccination Due Soon
- Overdue Vaccinations

---

# 💊 12. Deworming Management

Deworming records include:

- Animal
- Owner
- Date
- Product/Medicine Name
- Dose Information
- Next Due Date
- Notes

Upcoming deworming activities can be displayed through reminders.

---

# 📅 13. Appointment Management

Manage field appointments from the application.

### Appointment Information

- Date
- Time
- Owner
- Animal
- Phone
- Location
- Purpose
- Notes
- Status

### Appointment Status

- Pending
- Confirmed
- Completed
- Cancelled

---

# 🔔 14. Follow-up & Reminder System

The application provides reminders for:

- Treatment Follow-up
- AI Follow-up
- Pregnancy Check
- Vaccination
- Deworming
- Appointment
- Expected Calving

Example notification:

```text
Pregnancy check is due today
for Cow-COW-023.
```

---

# 📄 15. Reports & Export

The application supports reporting based on selected dates.

### Reports Include

- Monthly Treatment Summary
- Total Animals Treated
- Total Owners Served
- Species Breakdown
- Treatment Visits
- Follow-up Statistics
- AI Records
- Vaccination Records
- Deworming Records

### Export Formats

- PDF
- CSV

PDF reports are generated using Android's:

```text
android.graphics.pdf.PdfDocument
```

---

# 👤 16. Rabby Professional Profile

The application contains a dedicated professional profile.

### Profile

**Md. Shah Walimullah Rabby**  
Government AI Technician

**Amratali Artificial Breeding Center**

Upazila Prani Sampad Doptor & Veterinary Hospital  
Adarsha Sadar, Cumilla

📞 **01845-233917**

### Quick Actions

- 📞 Call
- 💬 SMS
- 📘 Facebook
- 📍 Google Maps

> The official Facebook profile/page URL should be configured with the verified link before production release.

---

# 🗺️ 17. Location & Google Maps

Owner locations can be stored using GPS coordinates.

Available actions:

- Open Map
- Navigate
- View saved location

Location permission should only be requested when required.

---

# 📸 18. Document Management

The application can support attachments such as:

- Animal Information
- Treatment Documents
- Prescription Note
- Test Reports
- Vaccination Documents
- Other Service Documents

---

# 📱 19. Offline-First Architecture

The application is designed for field work.

Core operations can work without internet:

- View Owners
- View Animals
- Add Owner
- Add Animal
- Add Treatment
- Add AI Record
- Add Vaccination
- Add Deworming
- Add Appointment
- View Treatment History
- Search Records

### Sync Status

```text
🟢 Synced
🟡 Syncing
🔴 Offline
```

A manual synchronization option is also available where cloud synchronization is configured.

---

# 🏗️ Architecture

```text
Rabby Animals Official
│
├── UI Layer
│   ├── Login
│   ├── Dashboard
│   ├── Owners
│   ├── Animals
│   ├── Treatments
│   ├── AI Management
│   ├── Vaccination
│   ├── Deworming
│   ├── Appointments
│   ├── Reports
│   └── Settings/Profile
│
├── ViewModel
│
├── Repository Layer
│   ├── Local Data
│   └── Cloud Sync
│
├── Room Database
│   ├── Owner
│   ├── Animal
│   ├── Treatment
│   ├── AI Record
│   ├── Pregnancy
│   ├── Vaccination
│   ├── Deworming
│   ├── Appointment
│   ├── Reminder
│   └── Activity Log
│
└── External Services
    ├── Firebase
    ├── Google Maps
    ├── Android Notifications
    └── PDF / CSV Export
```

---

# 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Java | Application Development |
| XML | Android UI |
| Android Studio | Development Environment |
| Material 3 | UI Design |
| Room Database | Local Data Storage |
| Firebase | Cloud / Authentication / Sync |
| Firebase Storage | File & Image Storage |
| Google Maps | Location & Navigation |
| Android Notifications | Reminders |
| PdfDocument | PDF Reports |
| CSV | Data Export |
| MVVM | Application Architecture |

---

# 🎨 Design

The application follows a clean Material 3 design.

### Design Principles

- Professional
- Simple
- User-friendly
- Fast
- Field-work focused
- Easy data entry
- Large readable controls
- Clear navigation
- Agricultural/veterinary visual identity

### Primary Brand Color

```text
#1B5E20
```

Emerald/dark green is used to represent:

- Agriculture
- Livestock
- Nature
- Veterinary services

---

# 🔐 Security & Privacy

The application contains potentially sensitive information such as:

- Owner phone numbers
- Owner addresses
- GPS coordinates
- Animal records
- Treatment history
- AI records

Therefore:

- Owner data should remain private.
- Treatment records should not be publicly accessible.
- Firebase security rules should restrict unauthorized access.
- Default PIN should be changed.
- Only necessary permissions should be requested.
- NID information should only be collected when necessary.
- Cloud backups should be properly secured.

---

# 🧪 Testing Checklist

Before production release, test:

- [ ] Login
- [ ] Logout
- [ ] PIN Change
- [ ] Remember Login
- [ ] Add Owner
- [ ] Edit Owner
- [ ] Delete Owner
- [ ] Search Owner
- [ ] Add Animal
- [ ] Edit Animal
- [ ] Animal History
- [ ] Add Treatment
- [ ] Treatment Search
- [ ] Date Filters
- [ ] Monthly Treatment Summary
- [ ] AI Record
- [ ] Pregnancy Check
- [ ] Expected Calving
- [ ] Vaccination
- [ ] Deworming
- [ ] Appointments
- [ ] Notifications
- [ ] PDF Export
- [ ] CSV Export
- [ ] Offline Mode
- [ ] Cloud Sync
- [ ] Phone Call
- [ ] SMS
- [ ] Facebook Link
- [ ] Google Maps
- [ ] Error Handling

---

# 🚀 Future Enhancements

Possible future versions:

- 👥 Multiple Technician Accounts
- 🖥️ Web Admin Dashboard
- 📱 Owner-Facing Mobile App
- 💬 SMS Notifications
- 💬 WhatsApp Integration
- 📅 Online Appointment Request
- 💊 Digital Prescription
- 🔳 QR Code Animal ID
- 🔳 QR Code Owner ID
- 🎙️ Bengali Voice Input
- 📊 Advanced Analytics
- ☁️ Automatic Cloud Backup
- 🌍 Multi-Center Support
- 🏢 Multi-District Deployment

---

# ⚠️ Professional Scope

Rabby Animals Official is primarily a **field-service and record-management application**.

It should not independently:

- Diagnose animal diseases
- Generate unauthorized medical prescriptions
- Replace professional veterinary judgment

Treatment and medicine information should be entered or approved by the responsible qualified professional.

---

# 📌 Project Status

**Status:** Completed Native Android Application

**Application:** Rabby Animals Official

**Category:** Animal Service & Artificial Breeding Management

**Primary User:** Md. Shah Walimullah Rabby

**Platform:** Android

**Architecture:** Offline-First

---

### Project Focus

```text
Animal Management
+
Treatment Management
+
Artificial Insemination
+
Pregnancy Tracking
+
Vaccination
+
Deworming
+
Appointments
+
Reports
+
Offline Field Service
```

---

# 📄 License

This project is intended for authorized/private use.

Before public distribution or open-source publication, choose an appropriate software license and review all personal, organizational, and service-related data included in the repository.

---

## 👤 Author

**MD. SHAH EMRAN HOSSAIN SABBIR**

- 🎓 Student at Green University of Bangladesh
- 💻 Department of Computer Science & Engineering
- 👨‍💻 Developed as a real-world Android application for digital livestock and field-service management.

---

## 📫 Contact Me

- 📧 **Email:** [sabbir223902002@gmail.com](mailto:sabbir223902002@gmail.com)
- 📱 **Phone:** +880 1521709658
- 🌐 **GitHub:** [shahsabbir223902002](https://github.com/shahsabbir223902002)

---

## 📱 App Demo

### 🎥 Application Demo

A complete demonstration of the **Rabby Animals Official** Android application is available below.

**Demo Video:**  
[▶️ Watch Rabby Animals Official App Demo](YOUR_DEMO_VIDEO_LINK_HERE)

The demo covers:

- 🔐 Login & Profile Lock
- 📊 Dashboard
- 👨‍🌾 Owner Management
- 🐄 Animal Management
- 🩺 Treatment Records
- 🔎 Treatment History & Date Filters
- 📈 Monthly Treatment Analytics
- 🐂 Artificial Insemination (AI) Management
- 🤰 Pregnancy Tracking
- 💉 Vaccination Management
- 💊 Deworming Management
- 📅 Appointment Management
- 🔔 Follow-up & Reminders
- 📄 PDF & CSV Reports
- 👤 Rabby Professional Profile
- 📞 Call & SMS Integration
- 📍 Google Maps Integration
- 📱 Offline-First Functionality
- ☁️ Data Synchronization

> **Note:** Replace `YOUR_DEMO_VIDEO_LINK_HERE` with the actual YouTube, Google Drive, GitHub, or other accessible demo-video link.

### 📸 Application Screenshots

You can also add screenshots of the main application screens here:

```text
Login Screen
Dashboard
Owner Profile
Animal Profile
Treatment History
AI Management
Reports
Settings



