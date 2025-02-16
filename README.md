# 🏥 Hospital Management System (HMS)

This is a **Hospital Management System** built using **Python** and **Excel (openpyxl, pandas)** for data storage. The system allows you to manage doctor, coworker, and patient records using an Excel file (`HMSEXCEL.xlsx`).

---

## 🚀 Features
- 📄 **Excel-Based Storage**: Stores all data in an Excel file (`HMSEXCEL.xlsx`).
- 🔍 **View Details**: Displays doctor, coworker, and patient records.
- ➕ **Add New Records**: Add new doctors, coworkers, and patients.
- ❌ **Delete Records**: Remove doctors, coworkers, or patients by ID.
- 🛠 **Error Handling**: Handles invalid inputs gracefully.

---

## 🛠 How It Works
1. If `HMSEXCEL.xlsx` **does not exist**, it **creates** the file with three sheets:
   - `doctordetails`: Stores doctor ID, name, specialization, and experience.
   - `coworkersdetails`: Stores worker ID, name, qualification, and position.
   - `patientdetails`: Stores patient token number, name, gender, age, and address.

2. The program provides a **menu** with the following options:
   - `1️⃣ Display the details`
   - `2️⃣ Add a new member`
   - `3️⃣ Delete a member`
   - `4️⃣ Exit`

3. **Data Entry:**
   - The user selects a category (Doctor, Co-worker, or Patient).
   - Enters the required details.
   - The data is **saved to the Excel file**.

4. **Data Deletion:**
   - The user enters the ID of the record to delete.
   - If the ID exists, the row is removed from Excel.

5. **Display Data:**
   - The user selects a category, and the corresponding data is displayed.

---

## ▶️ How to Run

### **🔹 Prerequisites**
Ensure you have **Python 3.x** installed and the required libraries:

```sh
pip install pandas openpyxl
