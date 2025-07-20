# Hospital Management System

A simple Java-based desktop application to manage hospital operations like doctor and patient records.

## Features

* Add, view, and manage **Doctors**
* Add, view, and manage **Patients**
* Basic command-line interface or GUI (depending on `HospitalMS.java` implementation)

## Tech Stack

* **Language:** Java
* **IDE:** IntelliJ IDEA
* **Database:** MySQL (using MySQL Connector/J)

## Project Structure

```
Hospital management system/
├── .idea/                 # IntelliJ project settings
├── Hospital management system.iml  # IntelliJ project module file
├── src/
│   └── HospitalManagementSystem/
│       ├── Doctor.java
│       ├── Patient.java
│       └── HospitalMS.java
```

## Setup Instructions

1. **Clone or Download** the project zip.
2. Open in **IntelliJ IDEA**.
3. Ensure **MySQL Connector/J** is properly linked (check `.idea/libraries/`).
4. Open the source files under `src/HospitalManagementSystem/`.
5. Configure your database connection inside the code if needed (check for `Connection` or `DriverManager`).
6. Run `HospitalMS.java` to start the application.

## Requirements

* Java JDK 8+
* MySQL database server
* IntelliJ IDEA (recommended)

## Author

This project was developed by \[Your Name Here].

Feel free to modify and extend the functionality!

---

 **Note:** Add SQL scripts if you use any database tables. Update connection details in the code accordingly.


