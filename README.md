# 🏪 Store Management System (Java + MySQL)

A fully functional **Store Management System** built using **Java (NetBeans)** and **MySQL Database**, packaged with an **EXE installer** and complete SQL database file.

This system helps manage store inventory, billing, product records, and database operations efficiently.

---

## 🚀 Features

### 📦 Inventory Management

* Add new products
* Update existing product details
* Delete products
* View product list

### 🧾 Billing System

* Generate bills
* Auto‑calculate totals
* Customer invoice support

### 🗄 MySQL Database Support

* Secure data storage
* Includes complete SQL backup file
* Easy import into phpMyAdmin or MySQL Workbench

### 💾 EXE Installer Included

* Fully packaged Windows application (.exe)
* No need for manual setup
* One‑click installation

---

## 🛠 Technologies Used

* **Java (NetBeans IDE)**
* **MySQL Database**
* **JDBC Connectivity**
* **Windows EXE Packaging**

---

## 📁 Project Structure

```
📦 store-management-system
│
├── store.exe                 # Application installer
├── store.sql                 # Database file
├── Requirements.txt          # System requirements
└── mysql-installer.msi       # MySQL installer (optional)
```

---

## 📦 Installation Guide

### 1️⃣ Install MySQL

If not installed, run:

```
mysql-installer-community.exe
```

Create database user and enable MySQL server.

### 2️⃣ Import Database

Open **phpMyAdmin / Workbench**, then:

```
Import → store.sql
```

### 3️⃣ Install the Application

Run:

```
store.exe
```

Follow the on‑screen installer instructions.

### 4️⃣ Launch the Software

After installation, open the Store Management System from desktop/start menu.

---

## 🔧 Detailed MySQL Setup (Required Before Running App)

### 🔹 Install & Configure MySQL

1. Double‑click **`mysql-installer-community-8.0.43.0.msi`**
2. Choose **Setup Type → FULL**
3. Click **Next → Execute** to install required components
4. Install **Microsoft Visual C++** if prompted
5. Continue clicking **Next** until configuration pages appear
6. When asked for password:

```
Username = root
Password = 1234
```

7. Proceed with **Next → Apply Configuration → Execute → Finish**

---

### 🔹 Restore Database (store.sql)

1. Open **MySQL Workbench** or **Command Line Client**
2. Login using:

```
Username = root
Password = 1234
```

3. Create database:

```
CREATE DATABASE store;
```

4. Open CMD where **store.sql** is located and run:

```
mysql -u root -p store < store.sql
```

5. When prompted, enter password:

```
1234
```

6. Verify import:

```
SHOW DATABASES;
USE store;
SHOW TABLES;
```

---

## 🔐 Requirements

* Windows 10/11
* Java Runtime (JRE)
* MySQL Server Installed

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## 📜 License

This project currently has **no license**. All rights reserved.

---

## 📩 Contact

For queries or improvements:
**Harshit Agarwal**
=======
# store-management-system
A desktop Store Management System built using Java (NetBeans) and MySQL, includes executable installer and SQL database file.

