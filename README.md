# Banker's Algorithm – Deadlock Avoidance (Operating System Lab)

## 📌 Project Overview

This project implements the Banker’s Algorithm for deadlock avoidance in Operating Systems. The program checks whether the system is in a safe state and finds the safe sequence of process execution.

---

## 🎯 Objectives

* Implement Banker’s Algorithm
* Calculate Need Matrix
* Determine Safe Sequence
* Check Safe or Unsafe State
* Understand Deadlock Avoidance

---

## 🛠️ Technologies Used

* Python 3.x
* Standard Python Libraries
* GitHub

---

## 📂 Project Structure

```
Bankers-Algorithm-Assignment
│
├── bankers_algorithm.py
├── README.md
├── report.pdf
├── output_screenshots
│   ├── need_matrix.png
│   ├── safe_sequence.png
│
└── input_example.txt
```

---

## ⚙️ How to Run the Program

1. Clone the repository:

```
git clone https://github.com/your-username/bankers-algorithm.git
```

2. Go to project folder:

```
cd bankers-algorithm
```

3. Run Python program:

```
python bankers_algorithm.py
```

4. Enter:

* Number of Processes
* Number of Resources
* Allocation Matrix
* Maximum Matrix
* Available Resources

---

## 📊 Formula Used

Need Matrix is calculated using:

Need = Maximum – Allocation

---

## 📈 Output

The program displays:

* Need Matrix
* Safe Sequence
* System Safe or Unsafe State

---

## ✅ Conclusion

Banker’s Algorithm helps in deadlock avoidance by ensuring that the system always remains in a safe state before allocating resources.

---

## 👨‍💻 Author

* Name: Nitin Barna
* Course: BCA (AI & DS)
* Subject: Operating System Lab

---

## 📚 References

* Operating System Concepts
* Python Documentation
