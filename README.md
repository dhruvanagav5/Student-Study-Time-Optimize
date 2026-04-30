# 📚 Student Study Time Optimizer

## 🎯 Project Overview

The *Student Study Time Optimizer* is a C++ project that helps students decide which subjects to study in order to maximize their total marks within a limited amount of available study time.

This project models a real-life scenario where students must make smart decisions about time management before exams.

---

## 🧠 Algorithm Used

*0/1 Knapsack using Dynamic Programming*

* Each subject is treated as an item
* Study time → Weight
* Marks → Value
* Objective → Maximize total marks within limited time

Dynamic Programming is used to efficiently compute the optimal solution by avoiding repeated calculations.

---

## 💡 Problem Statement

Given:

* A list of subjects
* Time required for each subject
* Marks weightage for each subject
* Total available study time

Find:

* The combination of subjects that maximizes total marks without exceeding available study time

---

## ⚙️ Features

* Efficient optimization using Dynamic Programming
* Clean and structured C++ implementation
* Displays maximum achievable marks
* Shows selected subjects clearly
* Modular code design (multiple files)

---

## 🏗️ Project Structure


study-optimizer/
│── main.cpp
│── optimizer.cpp
│── optimizer.h
│── subject.h
│── README.md


---

## ▶️ How to Compile and Run

### Step 1: Open terminal in project folder

### Step 2: Compile


g++ main.cpp optimizer.cpp -o app


### Step 3: Run


app.exe


---

## 📊 Sample Input


Subjects:
Math       Time=3   Marks=10
Physics    Time=4   Marks=12
Chemistry  Time=2   Marks=7
Biology    Time=5   Marks=15

Available Study Time: 7


---

## 📈 Sample Output


Maximum Marks Achievable: 22

Selected Subjects:
Physics (Time=4, Marks=12)
Math (Time=3, Marks=10)


---

## 🧩 How It Works

* A DP table is created where rows represent subjects and columns represent time
* Each cell stores the maximum marks achievable
* The table is filled using the recurrence relation of the 0/1 Knapsack problem
* Backtracking is used to determine selected subjects

---

## 🎓 Applications

* Study planning and exam preparation
* Time management optimization
* Resource allocation problems
* Decision-making systems

---

## 🚀 Conclusion

This project demonstrates how *Dynamic Programming* can be applied to solve real-world optimization problems efficiently. It provides a practical solution for students to maximize their academic performance with limited time.
