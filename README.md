# 📚 Library Management System

Welcome to the **Library Management System**, a Java-based desktop application designed to simplify and streamline book and staff management in any library.

> 🔧 Developed by: Ocean, Antriksh, Rohan, Tushar, and Rushil  
> 🛠️ Built using **Java (NetBeans IDE)** and **MySQL** for database integration.

---

## 🚀 Features

- 📖 **Books Management**
  - Add new books
  - View available books
  - Remove books

- 👨‍💼 **Staff Management**
  - Add new staff members
  - View existing staff
  - Remove staff

- 🔐 **Admin Login**
  - Secure login screen for library admins

---

## 💻 Tech Stack

| Frontend | Backend | Database |
|----------|---------|----------|
| Java Swing (NetBeans) | Java | MySQL |

---

## 🛠️ How to Run the Project

### Prerequisites

- 🔽 Install [NetBeans IDE](https://netbeans.apache.org/)
- 📦 Download **MySQL Connector/J (JAR file)** and add it to your project’s classpath

### Database Setup

1. Import the SQL file:
   - File: `library_database.sql` (located in the `/db` folder)

2. Create the following **three tables**:
   - `admin` – for login credentials
   - `books` – for storing book details
   - `staff` – for staff information

### Running the App

1. Open NetBeans IDE.
2. Import or open the project folder.
3. Add the MySQL connector `.jar` file to your project:
   - Right-click on project > Properties > Libraries > Add JAR/Folder
4. Run `LoginPage.java` to start the application.

---

## 📸 Screenshots

You can view how the app looks in real-time:

| Login Screen | Project Files |
|--------------|---------------|
| ![Login](./screenshots/login_screen.png) | ![Files](./screenshots/project_files.png) |


## 🙌 Credits

This project was a team effort developed under our college curriculum.

- Ocean 🌊  
- Antriksh 🚀  
- Rohan 🔧  
- Tushar 💡  
- Rushil 📘

---

## 📥 Contributions

Feel free to fork this repo and submit improvements or report bugs. Contributions are welcome!

---

## 📄 License

This project is intended for educational use only.
