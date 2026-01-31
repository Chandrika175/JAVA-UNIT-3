# Java Programming: Unit 3 - Advanced Concepts

This repository contains Java programs demonstrating core concepts from Unit 3, including System Packages, Exception Handling, Polymorphism, and Multithreading.

## 🚀 Topics Covered

### 1. Packages & User Input
- [cite_start]**Concepts**: Using the Java API (`java.util.Scanner`) to handle user input[cite: 937, 942].
- [cite_start]**Key Learning**: Understanding how to group related classes to keep applications organized and avoid naming conflicts[cite: 878, 882].

### 2. Exception Handling (Robustness)
- [cite_start]**Multiple Catch Blocks**: Handling different exceptions (like `ArithmeticException` and `ArrayIndexOutOfBoundsException`) in a single try block[cite: 1176, 1179].
- [cite_start]**Nested Try-Catch**: Providing granular error handling for complex operations[cite: 1185, 1186].
- [cite_start]**The `finally` Block**: Ensuring cleanup code (like closing resources) runs regardless of whether an error occurred[cite: 1213, 1214].
- [cite_start]**Manual Control**: Using `throw` to signal business rule violations and `throws` to delegate error handling to the caller[cite: 1200, 1205].

### 3. Object-Oriented Programming (OOP)
- [cite_start]**Inheritance & Polymorphism**: Demonstrating method overriding (runtime) and method overloading (compile-time) to create flexible and reusable code[cite: 757, 763].

### 4. Multithreading
- [cite_start]**Concepts**: Creating independent paths of execution by extending the `Thread` class[cite: 770, 778].
- [cite_start]**Thread Control**: Using methods like `sleep()` to pause execution and `join()` to coordinate between threads[cite: 799, 800].

## 🛠️ How to Run
Since these programs are designed for a single-file execution:
1. Copy the code from any `.java` file in this repository.
2. Paste it into an online compiler like [OnlineGDB](https://www.onlinegdb.com/online_java_compiler).
3. Ensure the class name containing the `main` method is named `Main` if required by the compiler.
4. Click **Run**.

## 📝 Key Notes from Study
- [cite_start]**Checked vs Unchecked**: Checked exceptions must be declared or handled at compile-time, while unchecked exceptions are typically programming errors[cite: 1141, 1174].
- [cite_start]**Thread Life Cycle**: Threads move through states: New → Runnable → Running → Blocked/Waiting → Terminated[cite: 791, 795].
