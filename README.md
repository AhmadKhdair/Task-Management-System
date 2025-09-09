# Task-Management-System
Developed a C-based CLI task manager using a linked-list backlog and a stack for performed tasks to enable O(1) undo. Supports loading tasks.txt, add/delete/search (ID or name), perform/undo, and summary Report.txt. Modular architecture, robust file I/O, defensive checks, and safe dynamic memory.


Menu-driven CLI for managing tasks using a singly linked list (backlog) and a stack (performed) for instant **O(1) undo**.

## Features
- Load from `tasks.txt` (`ID#Name#Date#Duration`), prevent duplicates
- Add / Delete / Search (by ID or name)
- Perform & Undo (LIFO)
- Summary report to `Report.txt`

## Build & Run
```bash
gcc -std=c11 -Wall -Wextra -O2 src/*.c -I include -o task_manager
./task_manager
