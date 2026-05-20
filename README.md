# Cybersecurity Attendance Logging Systems

A comprehensive technical showcase demonstrating two distinct architectural approaches to solving the same organizational problem: streamlining institutional attendance tracking and verification. 

This repository contains two completely independent versions of the system: a cloud-native mobile front-end application and a localized relational desktop database environment.

---

## 🛠️ System Comparison & Architectures

### 📱 Cloud-Native Version (Microsoft Power Apps)
Designed for modern, mobile-first environments. This web application offers a highly visual, touch-optimized user interface deployed rapidly via the cloud.
* **Key Feature:** Leverages live hardware interaction via an integrated camera verification component (`cam_Verification`) to capture photo logs at submission.
* **Backend Integration:** Connects seamlessly to cloud data structures for remote access.
* **File Included:** Cloud app platform export deployment package.

### 💾 Localized Desktop Version (Microsoft Access)
Designed for dedicated admin workstations, high-security offline environments, or localized office operations requiring zero cloud dependencies.
* **Key Feature:** An all-in-one relational database engine featuring rapid local data-entry forms (`FormCyberAttendanceLog`) and built-in local query tracking.
* **Backend Integration:** Utilizes a highly efficient, localized `.accdb` structural engine.
* **File Included:** `AttendanceSystem_JenniferRoxas.accdb` (Database File)

---

## 📦 Repository Contents

This repository hosts the distribution files for both system variants:
1. `AttendanceSystem_JenniferRoxas.accdb` : The complete Microsoft Access relational database and form engine.
2. `Cybersecurity_Attendance_Log_PowerApps.zip` : The complete canvas application package deployment file ready for Power Apps environment import.
