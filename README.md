# 🎓 Student Management System (Java)

A simple **console-based Java mini project** to manage student records using collections, file handling, and OOP concepts.

---

## 🚀 Features

* Add new student
* Remove student by ID
* Update student details
* Display students sorted by:

  * Name (Ascending)
  * GPA (Descending)
* Load student data from file

---

## 🛠️ Technologies Used

* Java (Core Java)
* Collections (ArrayList, Comparator)
* File Handling (BufferedReader, FileReader)
* Exception Handling
* OOP Concepts (Encapsulation, Classes, Objects)

---

## 📂 Project Structure

```
project-java-udemy/
│
├── src/
│   └── edu/mit/sms/
│       ├── Student.java
│       ├── StudentManagement.java
│
├── StudentData.txt
└── README.md
```

---

## ▶️ How to Run

### Step 1: Compile

```
javac src/edu/mit/sms/Student.java src/edu/mit/sms/StudentManagement.java
```

### Step 2: Run

```
java -cp src edu.mit.sms.StudentManagement
```

---

## 📌 Sample Menu

```
1. Add Student
2. Remove Student
3. Update Student
4. Display Students by Name
5. Display Students by GPA
6. Exit
```

---

## 📖 Concepts Covered

* Java Packages
* ArrayList & Collections
* Lambda Expressions
* File Reading
* Exception Handling
* Iterator usage

---

## ⚠️ Limitations

* Data is not saved after program exit
* University name is fixed ("MIT")
