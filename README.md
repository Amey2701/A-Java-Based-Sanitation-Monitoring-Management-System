
# 🧼 CleanTrack: A Java-Based Sanitation Monitoring & Management System

**CleanTrack** is a Java-based desktop application designed to help institutions monitor, manage, and ensure cleanliness and hygiene across facilities. With built-in modules for cleaning logs, maintenance records, and staff management, the application offers a reliable and scalable solution to automate sanitation workflows and ensure compliance with hygiene standards.


## 📘 Table of Contents

- [📘 Table of Contents](#-table-of-contents)
- [📌 Project Description](#-project-description)
- [🧩 Key Features](#-key-features)
- [🏗 System Modules](#-system-modules)
- [🛠️ Technologies Used](#-technologies-used)
- [📦 Project Structure](#-project-structure)
- [⚙️ Installation & Running the Project](#️installation--running-the-project)
- [📈 Future Enhancements](#-future-enhancements)
- [🎯 Learning Outcomes](#-learning-outcomes)
- [👨‍💻 Author](#-author)
- [📜 License](#-license)


## 📌 Project Description

This project addresses the need for automated hygiene supervision in public and private institutions such as hospitals, schools, societies, and offices. Manual tracking of cleaning tasks often leads to inefficiencies and non-compliance.

**CleanTrack** solves this by providing:

- A centralized platform for sanitation task management
- A clean and intuitive Java Swing GUI
- Integrated database for offline operation and real-time updates



## 🧩 Key Features

✅ **Role-Based Login System** – Admin and staff user roles  
✅ **Task Logging** – Record and monitor sanitation and maintenance activities  
✅ **Hygiene Dashboard** – View real-time cleaning status and alerts  
✅ **Data Visualization** – Table-based record views with update/delete options  
✅ **Offline Capability** – Fully functional with local Derby database  
✅ **Lightweight & Fast** – Built for low-resource environments


## 🏗 System Modules

| Module                  | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `login.java`            | Handles secure authentication (Admin/Staff)                                |
| `register.java`         | Staff/employee registration with validation                                |
| `mainpage.java`         | Dashboard providing navigation and summary                                 |
| `cleaningSystem.java`   | Cleaning task entry and review interface                                   |
| `maintenanceSystem.java`| Tracks infrastructure repair and issues                                    |
| `ViewTables.java`       | Visual display of database entries                                         |
| `updateinfo.java`       | Edit or update existing records                                            |


## 🛠️ Technologies Used

| Component           | Tech Stack / Tools                 |
|---------------------|------------------------------------|
| Programming Language| Java                               |
| GUI Framework       | Java Swing                         |
| Database            | Apache Derby DB (Embedded)         |
| IDE                 | Apache NetBeans                    |
| Libraries           | `beansbinding`, `rs2xml`, JavaFX   |
| Build Tool          | Apache Ant / NetBeans Build System |



## 📦 Project Structure

```

CleanTrack/
│
├── src/
│   └── System/
│       ├── \*.java             # Main modules like login, register, cleaning
│       ├── \*.form             # GUI form files for NetBeans
│       └── resourses/         # Icons, images for UI
│
├── lib/                       # External JARs: JavaFX, Derby, binding libs
├── database/                  # Apache Derby database files
├── nbproject/                 # NetBeans project settings
├── build.xml                  # Build configuration
├── manifest.mf                # Manifest for packaging JAR

```



## ⚙️ Installation & Running the Project

### 🔧 Requirements

- Java JDK 8 or higher
- Apache NetBeans IDE (preferably 12+)
- Derby DB (comes with NetBeans)
- No Internet required (offline capable)

### 🧪 Run Steps

1. Open the project in NetBeans.
2. Clean and Build the project from the IDE.
3. Right-click `login.java` or `mainpage.java` → **Run File**.
4. Application will launch with the login screen.
5. Derby DB will auto-connect locally (ensure permissions if needed).



## 📈 Future Enhancements

- ☁️ Cloud database integration for centralized monitoring  
- 📱 Mobile-friendly or web-based version using React or Flutter  
- 🔔 Notifications/reminders for pending sanitation tasks  
- 📊 Hygiene scoring and analytics dashboard  
- 🛡️ User access logs and audit trail tracking  



## 🎯 Learning Outcomes

- Built a **complete GUI application** using Java Swing  
- Applied **database integration** with Derby using JDBC  
- Gained experience with **event-driven programming**  
- Practiced modular coding, JAR packaging, and NetBeans project structuring  



## 👨‍💻 Author

**Amey Mali**  
📫 [GitHub](https://github.com/Amey2701)  
🏢 Sai Shradhha Housing Society, Floor No.203, Devnagari, Pen, Raigad  
🗓️ April 2025



## 📜 License

This project is created for educational and demonstration purposes.  
All rights reserved © 2025.
```
