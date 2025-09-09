# Task-Management-System
A lightweight Task Management System to practice and demonstrate core data-structure skills in a real, useful scenario. It lets you manage a backlog, execute tasks, and instantly undo the last action—mirroring features in real productivity tools while keeping the codebase small and educational.
Benefits

Shows how to model real operations (add/search/delete/perform/undo) with custom structures.

Emphasizes algorithmic trade-offs: O(1) stack ops vs. linear list scans.

Trains safe file I/O, dynamic memory, and defensive programming.

Produces a clear summary report you can share or audit.

What I used in the implementation

Language: C (procedural)

Data Structures:

Singly Linked List for unperformed tasks (backlog)

Stack (LIFO) for performed tasks to enable O(1) undo

Memory Management: malloc/free, pointer manipulation, ownership clarity

File I/O & Parsing: load tasks from tasks.txt (ID#Name#Date#Duration), generate Report.txt

APIs/Libs: <stdio.h>, <stdlib.h>, <string.h>

Program Structure: modular functions (add/search/remove/perform/undo/print), separation of concerns between list and stack

Error Handling: checks for empty list/stack, duplicate IDs, file open/format errors

Complexity Notes:

Stack push/pop/top: O(1)

List search/remove: O(n)

Key Features

Load tasks, prevent duplicates, add/delete/search (by ID or name)

Perform a task (moves to stack) and Undo Last Performed Task

View unperformed/performed tasks

Generate a structured summary report (Report.txt)
