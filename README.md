# Customized File System (CFS)

## 📌 Introduction
The **Customized File System (CFS)** is a study-based project that represents a simplified version of the Linux file subsystem and the secondary storage file system.  
It combines data structures from the Linux file system and hard disk storage to provide basic file manipulation functionalities such as **create, open, read, write, truncate**, etc.

This project helps in understanding the internal working of file systems by implementing them using **C/C++** and data structures like **linked list, arrays**, etc.

---

### Interface
- Command-line shell interface  

---

## 🚀 Proposed System
- A **virtual representation** of a file system.  
- Provides functionality similar to Linux file system.  
- Implements all essential data structures such as:  
  - **INODE Table (Incore INODE)**  
  - **File Table**  
  - **UAREA**  
  - **User File Descriptor Table (UFDT)**  
- Includes a **customized shell** to interact with the system.  

---

## 🔑 Commands Implemented
- `create` → Create a new regular file.  
- `fstat` → Display information about a file.  
- `ls` → List all files with details.  
- `help` → Show available commands.  
- `man` → Show information about a command.  
- `truncate` → Remove data from a file.  

---

## 📊 System Diagrams
- **Processed Flow Diagram**  
- **Block Diagram of File System**  

(*See repo for diagrams and detailed explanation*)  

---

## 📚 What We Learned
- Internal structure and functions of Linux file system.  
- How file system data structures work in **C and C++**.  
- How a **customized shell** can be designed to simulate file system operations.  

---

## 📖 References
- *The Linux Programming Interface* by Michael Kerrisk  
- UNIX/Linux Documentation  
- [Virtual File System (Wikipedia)](https://en.wikipedia.org/wiki/Virtual_file_system)  
- [File System (Wikipedia)](https://en.wikipedia.org/wiki/File_system) 

---
## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Run the file system

```bash
g++ CFS.cpp -o CFS
./CFS
```

----

### Usage 
```
    man command_name
    or
    help
```

