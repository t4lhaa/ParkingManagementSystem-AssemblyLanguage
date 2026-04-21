## 🚗 Parking Management System (Assembly - Irvine32)

---

### 📌 Overview

* This is a **Parking Management System** written in **x86 Assembly Language**
* Uses the **Irvine32 library**
* Manages vehicle parking, counts, and revenue
* Stores and loads data from a file

---

### ✨ Features

* Add vehicles:

  * Rikshaw 🛺
  * Car 🚗
  * Bus 🚌
* Remove vehicles
* Maximum capacity limit (10 vehicles)
* Automatic fee system:

  * Rikshaw → $1
  * Car → $2
  * Bus → $3
* Show parking records
* Save records to file
* Load previous records on startup
* Clear all records
* Input validation and error handling

---

### 🧠 Concepts Used

* Assembly Language (x86)
* Irvine32 Library
* File Handling (Read/Write)
* Procedures and Modular Programming
* Loops and Conditions
* String Processing

---

### 📋 Menu Options

* 1 → Add Rikshaw
* 2 → Add Car
* 3 → Add Bus
* 4 → Show Records & Save
* 5 → Remove Vehicle
* 6 → Clear All Records
* 7 → Clear Screen
* 8 → Exit Program

---

### 💾 File Handling

* Data is saved in:

  * `parking_records.txt`
* On startup:

  * Program loads previous data if file exists
  * Otherwise starts fresh

---

### ⚠️ Error Handling

* Invalid input (non-numeric)
* Parking full
* Removing non-existing vehicles
* File errors

---
* Invalid menu choices

-
