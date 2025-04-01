# 📚 Course Scheduler (CS221 Course)

## 📝 Overview
This project is a course scheduling system that utilizes an embedded database to store, manage, and retrieve academic scheduling information. It is likely part of a Java application or backend system that interacts with the Derby database engine.

## 🗂️ Project Structure
```
CourseSchedulerDByzh5492/
├── db.lck
├── log/
├── seg0/
├── tmp/
├── service.properties
├── README_DO_NOT_TOUCH_FILES.txt
```

- **db.lck**: Lock file for Derby database instance
- **log/**: Transaction and activity logs
- **seg0/**: Stores actual table data
- **service.properties**: Configuration file for the database
- **tmp/**: Temporary data for DB processes
- **README_DO_NOT_TOUCH_FILES.txt**: Warning to avoid manual changes to the DB files

## ⚙️ Requirements
- Java Development Kit (JDK)
- Apache Derby (or a Java app using embedded Derby)
- Optional: Java GUI or CLI interface to interact with the database

## ▶️ How to Use
1. Clone or unzip the project into your working directory.
2. Start your Java application that connects to this embedded Derby database.
3. Ensure no files in the `CourseSchedulerDByzh5492` folder are manually edited or removed.

## 📌 Notes
- Do **not** modify the files inside the Derby database folder directly.
- Always interact with the database through your Java program or via SQL commands using a supported Derby interface.

## 👤 Author
Ya-Nuo, Hsu
