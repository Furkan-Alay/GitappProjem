# 📋 Prerequisites

- **JDK 11**
- **Maven 3**
- **MySQL 8**

---

# ⚙️ Technologies Used

- **Spring MVC**
- **Spring Security**
- **Spring Data JPA**
- **Maven**
- **JSP**
- **MySQL**

---

# 🗄️ Database Setup

This project uses **MySQL** as the database.

### 📌 MySQL Installation (for Ubuntu 14.04)

```bash
sudo apt-get update
sudo apt-get install mysql-server
```

📥 Importing the Database

After installing MySQL:
1. Locate the database dump file:
```bash
/src/main/resources/db_backup.sql
```

2. Locate the database dump file:
```bash
mysql -u <your_username> -p accounts < db_backup.sql
```

Replace <your_username> with your MySQL username.

accounts is the database name where the dump will be imported.

📌 Notes

Ensure that MySQL server is running before importing the dump.

You can adjust the database connection settings in the application configuration files as needed.
