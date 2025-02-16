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

### Prerequisites
Ensure you have Python 3.x installed and the required libraries. Run the following command in your terminal:

    pip install pandas openpyxl

### Running the Program
Clone the repository and navigate to the project directory by running:

    git clone https://github.com/Amarnath-216/hospital-management-system.git
    cd hospital-management-system
    python hospital_management.py

---

## 📝 Usage Example

:::::::::::::::::::: HOSPITAL MANAGEMENT SYSTEM :::::::::::::::::::::
                
                1. Display the details
                2. Add a new member
                3. Delete a member
                4. Make an exit

Enter your Choice: 1

                1. Doctors Details
                2. Co-worker Details
                3. Patient Details

Enter your choice: 1

If the data exists, it will be displayed; otherwise, a message will indicate that it's empty.

---

## 🛠 Future Enhancements
- **Update Functionality**: Ability to modify existing records.
- **GUI Interface**: Implement a Tkinter or Flask-based UI.
- **Search Feature**: Allow users to search for specific records.
- **Analytics Dashboard**: Generate reports and insights from stored data.

---

## 📌 Author
- **Amarnath P**  
- GitHub: [Amarnath-216](https://github.com/Amarnath-216)

---
