# Bank Management System

A lightweight, terminal-based Bank Management System written in C. This project demonstrates core backend concepts including dynamic memory management, file I/O for persistent data storage, and transactional processing.

##  Features
* **Dynamic Memory Allocation:** Efficiently manages account records in memory using pointers and dynamic arrays, ensuring scalable resource usage.
* **Persistent Storage:** Utilizes C standard File I/O to read from and write to a local text file, ensuring transactional data is saved between sessions.
* **CRUD Operations:** Supports creating, viewing, updating, and deleting bank accounts through a centralized data structure.
* **Interactive Terminal UI:** Provides a clean, menu-driven interface for seamless user transactions.

##  Tech Stack & Skills
* **Language:** C
* **Core Concepts:** Pointers, Structs, File Handling, Manual Memory Management (`malloc`, `free`), Modular Programming.

##  How to Run

1. Clone the repository to your local machine.
2. Ensure your data text file (e.g., `accounts.txt`) is located in the same root directory as the source files.
3. Compile the program using GCC (adjust filenames based on your structure):
   ```bash
   gcc main.c bank_system.c -o bank_app
   ```

## Excute on windows
    .\bank_app.exe
## Excute on Linux/Mac
    ./bank_app
