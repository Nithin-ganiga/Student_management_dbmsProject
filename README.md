## **Student Management System (DBMS Mini Project)**
🚀 A **Flask and MySQL-based Student Management System** for handling student records efficiently.

---

### **📌 Project Overview**
The **Student Management System** is a **web-based application** that helps manage student details, including **personal information, attendance, and academic records**.  

This project follows **database management principles**, providing **authentication, role-based access, and CRUD operations** on student records.  

---

### **🛠 Tech Stack Used**
#### **Frontend:**
- HTML, CSS, JavaScript  
- Bootstrap (for styling)  

#### **Backend:**
- **Flask (Python Framework)**
  - User authentication (Flask-Login)
  - Database operations (Flask-SQLAlchemy)
- **MySQL Database** (for student records)  
- **Werkzeug Security** (for password hashing)
- 
---

### **🎯 Features**
✅ **Student Management**: Add, update, delete student records  
✅ **Attendance Tracking**: Store and retrieve student attendance  
✅ **User Authentication**: Secure login/signup (Flask-Login)  
✅ **Search Functionality**: Quickly find student records  
✅ **Role-Based Access**: Admin access for student record management  
✅ **Trigger Logging**: Database triggers to track updates  

---

### **🚀 Installation & Setup**
#### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/Nithin-ganiga/Student_management_dbmsProject.git
cd Student_management_dbmsProject
```

#### **2️⃣ Set Up the Virtual Environment**
```sh
pip install virtualenv
virtualenv venv
source venv/bin/activate  (Linux/macOS)
venv\Scripts\activate     (Windows)
```

#### **3️⃣ Install Dependencies**
```sh
pip install -r requirements.txt
```

#### **4️⃣ Set Up MySQL Database**
- Open MySQL and create a database:
  ```sql
  CREATE DATABASE student_database;
  ```
- Import the `schema.sql` file:
  ```sh
  mysql -u root -p student_database < database/schema.sql
  ```

#### **5️⃣ Run the Application**
```sh
python main.py
```
- The server will start at **http://127.0.0.1:5000/**  
---

### **📌 Future Enhancements**
🔹 **Email Notifications** for students  
🔹 **Graphical Attendance Report (Charts.js)**  
🔹 **Machine Learning for Performance Prediction**  
🔹 **Mobile App Integration (React Native/Flutter)**  
---

### **📜 License**
This project is **open-source** and available under the **MIT License**.

---

### **📫 Contact**
📧 Email: [nithinganiga959@gmail.com](mailto:nithinganiga959@gmail.com)  
💼 LinkedIn: [Nithin Ganiga](https://www.linkedin.com/in/nithin-ganiga-22249724a/)  

---

### **🌟 Star this Repository!**  
If you like this project, don’t forget to ⭐ it! 😊  

---
