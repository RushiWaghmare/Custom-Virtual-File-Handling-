# Custom Virtual File System (CVFS) in C

This project demonstrates a **Custom Virtual File System (CVFS)** implemented in C, simulating a Unix-like file system entirely in memory. It supports standard file operations and manages its own metadata, memory, and file descriptors.

## 🧠 Developer

* [Rushikesh Waghmare](https://github.com/RushiWaghmare)

## 🚀 Project Overview

CVFS allows users to perform file operations such as `create`, `read`, `write`, `open`, `close`, `ls`, `rm`, and `truncate`. It uses custom data structures to manage files, metadata, and disk space, providing a low-level understanding of file systems in C.

### ✨ Features

* Command-line interface with user-defined shell commands
* File operations: `create`, `read`, `write`, `open`, `close`, `ls`, `rm`, `truncate`
* Custom data structures:

  * **Inode Table** for file metadata
  * **Superblock** for free block and inode tracking
  * **UFDT** (User File Descriptor Table)
  * **File Table & DILB** (Disk Inode List Block)
* File-level permissions and reference counting
* Dynamic memory allocation
* Demonstrates pointers, linked lists, and memory management in C

## 🧰 Tech Stack

* **Language**: C
* **Concepts**: File Systems, Pointers, Linked Lists, Memory Management, Command Parsing, File I/O

## 🛠️ Getting Started

### Prerequisites

* C compiler (GCC recommended)
* Git

### Installation

1. Clone the repository:

```bash
git clone https://github.com/RushiWaghmare/Virtual-File-Handling-
cd Virtual-File-Handling-
```

2. Compile the program:

```bash
gcc CVFS.c -o cvfs
```

### Running the Program

Run the executable:

```bash
./cvfs
```

Example commands:

```bash
create myfile.txt
write myfile.txt "Hello CVFS"
read myfile.txt
ls
rm myfile.txt
close myfile.txt
```

## 🎯 Learning Outcomes

* Understanding low-level file handling in C
* Practical experience with pointers, memory allocation, and linked lists
* Simulated Unix-like file system implementation
* Command-line interface design
