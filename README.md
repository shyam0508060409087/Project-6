# Project-6


# 📦 Java Mini Projects – Stack Applications

This repository contains two mini projects built during **Week 6** of my upskilling journey focused on mastering the **Stack** data structure in Java. Both projects demonstrate practical applications of stack operations using Java’s built-in `Stack` class.

---

## 🔹 Project 1: Balanced Brackets Checker

### 📄 Description

This program checks whether the given expression contains **balanced brackets**. It supports parentheses `()`, square brackets `[]`, and curly braces `{}`.

### 🧠 Concepts Used

* Stack (LIFO principle)
* Character traversal in strings
* Conditional matching of brackets

### 🛠️ How it works

* Push opening brackets to the stack.
* On encountering a closing bracket, check if the top of the stack matches the corresponding opening bracket.
* Return false if mismatch occurs or if the stack is empty before finishing.
* Return true only if stack is empty at the end.

### ✅ Sample Input/Output

```
Input: {[(a+b)+c]*d}
Output: Balanced expression

Input: (a+b]*(c+d)
Output: Not balanced
```

---

## 🔹 Project 2: Reverse a String Using Stack

### 📄 Description

This program demonstrates how to **reverse a string using a stack**. It pushes each character of the input string onto a stack and then pops them off to create the reversed version.

### 🧠 Concepts Used

* Stack-based reversal
* StringBuilder for efficient string manipulation
* Stack operations: push and pop

### 🛠️ How it works

* Traverse the string and push each character onto the stack.
* Pop characters one by one and append to the result.
* Print the reversed string.

### ✅ Sample Input/Output

```
Input: hello
Output: olleh

Input: Stack
Output: kcatS
```

---

## 📂 Project Structure

```
Week6_Stack_Projects/
├── BalancedBracketsChecker.java
├── StringReverser.java
└── README.md
```

---

## 📌 Learning Highlights

* Applied **stack operations** in real-world scenarios
* Practiced both **algorithmic logic** and **Java implementation**
* Improved understanding of how **LIFO** is used in bracket validation and reversal tasks

