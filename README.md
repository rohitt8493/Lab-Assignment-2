# 🎓 Student Management System (Java) – Lab Assignment 2

## 📌 Overview
This project is a **Java-based Student Management System** developed as part of **Java Lab Assignment 2** at Netaji Subhas University of Technology (NSUT), Delhi.  
It demonstrates advanced **Object-Oriented Programming (OOP)** principles including **inheritance, polymorphism, abstract classes, interfaces, and modular design**.

---

## 🛠 Features
- Abstract class **Person** with common fields (`name`, `email`).
- Concrete class **Student** extending Person with additional fields (`rollNo`, `course`, `marks`, `grade`).
- Interface **RecordActions** defining CRUD operations:
  - `addStudent()`
  - `deleteStudent()`
  - `updateStudent()`
  - `searchStudent()`
  - `viewAllStudents()`
- **StudentManager** class implementing RecordActions with:
  - Prevention of duplicate roll numbers.
  - Efficient record management using `List<Student>` and `HashMap<Integer, Student>`.
- Demonstrates:
  - **Method Overloading** (e.g., overloaded display methods in Student).
  - **Method Overriding** (e.g., overriding `displayInfo()`).
  - **Polymorphism** (static and dynamic).
- Organized into **packages** (`model`, `service`) for modular design.

---

## 📂 Class Design
### Class Hierarchy
- **Person** (abstract class)
  - Fields: `name`, `email`
  - Method: `displayInfo()`
- **Student** (extends Person)
  - Fields: `rollNo`, `course`, `marks`, `grade`
  - Methods: `displayInfo()` (overridden), overloaded display methods
- **RecordActions** (interface)
  - Methods: `addStudent()`, `deleteStudent()`, `updateStudent()`, `searchStudent()`, `viewAllStudents()`
- **StudentManager** (implements RecordActions)
  - Implements CRUD operations with validation and storage
 

---

## 📑 Expected Output

---

## Name= Rohit Kumar
## Roll no = 2401010255
