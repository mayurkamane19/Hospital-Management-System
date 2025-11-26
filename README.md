Here is a **perfect, clean, professional README.md** for your HMS Major Project.
You can copy-paste directly → **README.md** (fully formatted).

---

# 🏥 Hospital Management System (HMS) – Major Project

### **Role-Based | Jupyter Compatible | Tkinter + CustomTkinter GUI | CSV Database | PDF Billing**

This project is a complete **Hospital Management System (HMS)** built using **Python**, **CustomTkinter**, **FPDF2**, and **Matplotlib**, designed to run **inside Jupyter Notebook** using a **separate GUI thread**.

It includes full functionality for hospital operations, including patients, doctors, appointments, billing, medicine inventory, rooms, and admin management.

---

## 🚀 Features

### **🔐 Authentication**

* Admin & Doctor login (role-based access)
* Secure user storage in CSV
* Admin can create/remove users

---

### **🧑‍⚕️ Patient Management**

* Patient registration form
* Search/filter by:

  * Patient ID
  * Name
  * Gender
  * Assigned Doctor
* View and manage patient list
* Generate **Patient PDF Summary**
* Book appointment from patient actions

---

### **📅 Appointments**

* Book appointments
* List all appointments
* Cancel appointments

---

### **💊 Medicine Inventory**

* Add / update medicines
* Delete medicines
* Track quantity and price
* Automatically reduce stock when used in billing

---

### **🛏️ Room Management**

* Assign a room to a patient
* Free existing rooms
* Check occupancy status

---

### **🧾 Billing System**

* Enter room charge, doctor fee, medicines used
* Automatically calculates:

  * Medicine cost
  * Total bill
* Reduces medicines stock
* Saves bill record to CSV
* Generates **PDF Bill Slip**

---

### **📊 Dashboard (Admin Only)**

* Overview stats:

  * Total Patients
  * Appointments Count
  * Bills Count
  * Medicines Count
  * Occupied Rooms Count
* Graph:

  * **Patients Registered Per Day** (Matplotlib)

---

### **📚 Data Storage (CSV Files)**

All data stored in CSV:

* `hms_patients.csv`
* `hms_appointments.csv`
* `hms_bills.csv`
* `hms_users.csv`
* `hms_rooms.csv`
* `hms_medicines.csv`

No SQL database required.

---

## 🛠️ Technologies Used

| Component      | Library                        |
| -------------- | ------------------------------ |
| GUI            | `tkinter`, `customtkinter`     |
| PDF generation | `fpdf2`                        |
| Graph plotting | `matplotlib`                   |
| Data storage   | CSV                            |
| Threading      | Used to run GUI inside Jupyter |

---

## 📦 Installation

Install required packages:

```bash
pip install customtkinter fpdf2 matplotlib
```

---

## ▶️ Running the Project (Jupyter Notebook)

Just copy the entire code into **one Jupyter cell** and run:

✔ GUI starts in a separate thread
✔ Notebook stays responsive

No extra configuration required.

---

## 📁 Folder Structure

```
📦 HMS Project
 ┣ 📜 hms_patients.csv
 ┣ 📜 hms_appointments.csv
 ┣ 📜 hms_bills.csv
 ┣ 📜 hms_users.csv
 ┣ 📜 hms_rooms.csv
 ┣ 📜 hms_medicines.csv
 ┣ 📜 HMS_Main.py (optional if using Python script)
 ┗ 📜 README.md
```

---

## 👤 Default Login Credentials

### **Admin**

```
Username: admin
Password: admin123
```

### **Doctor**

```
Username: drraj
Password: doctor123
```

⚠️ New doctor accounts can be created using:

* Quick Create Doctor button (on login screen)
* Admin Users Panel

---

## 📌 Important Notes

* GUI uses **CustomTkinter**, so theme is modern and responsive.
* PDF bills are saved automatically in the working directory.
* Medicines stock is auto-updated when billing.
* CSV files auto-create if missing.
* Works on **Windows, Mac, Linux**.

---

## ✨ Screens Included

* Login Screen
* Dashboard
* Patients Panel
* Appointments Panel
* Billing System
* Medicines Inventory
* Rooms Management
* Bills History
* Users Panel (Admin only)

---

## 🧑‍💻 Developer Info

**Author:** *Mayur Kamane*
**Project Type:** Major Project – Python GUI
**Suitable For:**

* Final Year Submission
* Resume Projects
* Python GUI Portfolio

---

If you want, I can also generate:

✅ **Project Report (40+ pages)**
✅ **Abstract**
✅ **ER Diagram**
✅ **UML Diagrams**
✅ **IEEE Format Documentation**
✅ **PowerPoint Presentation**

Just tell me **"Create project report"** and I’ll generate everything!
