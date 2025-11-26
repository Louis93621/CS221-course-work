# 📚 Course Scheduler (CS221 Course)

## 📝 Overview
This project is a course scheduling system built with **Java Swing** that interacts with an **Apache Derby database (Network Server mode)** to store, manage, and retrieve academic scheduling information.

## 🗂️ Project Structure
```
Project Root/
├── src/
│   ├── MainFrame.java        (GUI Entry Point)
│   ├── DBConnection.java     (Database Configuration)
│   └── ... (Queries files)
├── CourseSchedulerDByzh5492/ (Database Folder)
└── README.md
```

- **src/**: Contains the Java source code and application logic.
- **CourseSchedulerDByzh5492/**: Stores the embedded Apache Derby database files. **Note: Do not modify or delete files inside this directory to prevent data corruption.**

## ⚙️ Requirements
- Java Development Kit (JDK)
- Apache Derby Database Server (configured on port 1527)
- NetBeans IDE (Recommended for easy DB management)

## ▶️ How to Use
1. Clone or unzip the project.
2. **Start the Apache Derby Network Server** on `localhost:1527`.
   - *If using NetBeans:* Go to `Services` > `Databases` > Right-click `Java DB` > `Start Server`.
3. Run `MainFrame.java` to start the application.
4. Ensure the `CourseSchedulerDByzh5492` folder exists in the project root relative to the execution path.

## 📌 Notes
- Do **not** modify the files inside the `CourseSchedulerDByzh5492` folder directly.
- The default database credentials are set to user: `java`, password: `java` (defined in `DBConnection.java`).

## 👤 Author
Ya-Nuo Hsu (Louis)
