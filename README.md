# 📦 jpaOnlyDataBase

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/PeeterDalVitt/jpaOnlyDataBase/blob/main/LICENSE)

A small Spring + JPA project designed as a practical exercise in persistence, table mapping, and MySQL configuration. This project serves as a refresher on entity relationships, database connection troubleshooting, and classic Java SE integration using Hibernate and JPA.

---

## 🔧 Technologies Used

- Java 17  
- JPA (with `persistence.xml`)  
- Hibernate  
- MySQL  
- Maven

---

## 🚀 How to Run

1. Clone this repository  
2. Open it with your preferred IDE (e.g., IntelliJ, Eclipse with SpringTools)  
3. Make sure MySQL is running and create a database named `aulajpa`  
4. Open `src/main/resources/META-INF/persistence.xml` and update your MySQL user/password  
5. Run the `Program` class (`aplicacao/Program.java`) as a Java Application  

This will create a table named `pessoa` and insert a few sample entries.

---

## 📚 What You’ll Find

- Basic JPA configuration using `persistence.xml`
- Entity mapping with `@Entity`, `@Id`, and `@GeneratedValue`
- Automatic schema creation via `hibernate.hbm2ddl.auto=update`
- A neat playground for revisiting JDBC, object-relational mapping, and app-database flow

---

## 📝 License

This project is licensed under the [MIT License](https://github.com/PeeterDalVitt/jpaOnlyDataBase/blob/main/LICENSE).
