# Student-Database-management system.
The Student Database Management System is a database project designed to manage  student information in an educational institution.  Many schools and training centers still rely on manual or poorly organized systems to store  student records, which leads to data duplication, inconsistency, and difficulty in accessing  information.
## 🛠️ Tools Used
- MySQL  
- SQL (Structured Query Language)  
- MySQL Workbench  
- GitHub  
- ER Diagram Tool (Draw.io or Lucidchart)  

---

## 📌 Problem Statement
Educational institutions need a reliable way to store and manage student information such as personal details, enrollment data, and academic programs.  

Without a structured database system, institutions face challenges such as:  

- Duplicate student records  
- Difficulty updating student information  
- Poor data organization  
- Slow retrieval of student details  

---

## 🎯 Project Goal
The goal of this project is to design a well-structured database that solves these problems using proper database design principles.
## 📋 Project Questions / Tasks

---

### 1️⃣ Database Model
- Explain the relational database model and why it is suitable for managing student data.  
- Compare it with other database models such as:
  - Hierarchical model  
  - Network model  

---

### 2️⃣ Entities, Relationships, and Attributes

### Entities:
1. **Students**
2. **Departments**

### Attributes:

#### Students Table:
- student_id (PK)
- first_name
- last_name
- gender
- date_of_birth
- enrollment_year
- department_id (FK)

#### Departments Table:
- department_id (PK)
- department_name

### Relationship:
- One department has many students (1:M)

---

### 3️⃣ Normalization
Initially, all student information is stored in a single table that includes:
Normalize to **Third Normal Form (3NF)**:

- Separate **Departments**
- Use **department_id** as foreign key in Students

#### Tasks:
-  normalization Prevents storing the same data in multiple places, saving storage space and minimizing update errors. 



















![er diagram for student management system](https://github.com/adadugenesis-blip/Student-Database-management/blob/204f9b15a9362c7b105c29b7ba30cf7a851f7c9d/Screenshot%202026-02-20%20114417.png)
