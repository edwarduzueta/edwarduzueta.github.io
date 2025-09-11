---
layout: project
type: project
image: img/database.png
title: "Database Application"
date: 2024-12-01
published: true
labels:
  - C
  - C++
  - Data Structures
  - File I/O
summary: "Implemented a sorted linked list database in C, later extended into C++ with classes and file persistence."
---

This project was a menu-driven database application first built in **C** and later extended into **C++**.  
It used a **sorted linked list** to store account records, keeping them in ascending order by account number.  
The program supported adding, finding, deleting, and printing records, while also saving and loading records to a file.  

<div class="text-center p-3">
  <img src="../img/databas.png" alt="Database Screenshot" width="400px" class="img-thumbnail">
</div>

For the C version, I implemented functions such as `addRecord`, `printAllRecords`, `findRecord`, and `deleteRecord`.  
The C++ version encapsulated this logic inside a custom `llist` class, adding object-oriented structure to the program.  

Key challenges included:
- Managing dynamic memory safely (avoiding leaks)  
- Designing insertion logic to maintain sorted order  
- Building file I/O to persist data between runs  
- Transitioning procedural code into an object-oriented design  

Here is a code snippet showing how a record was inserted in sorted order:

```cpp
if (list == NULL || newRecord.accountno < list->accountno) {
    newRecord->next = list;
    list = newRecord;
} else {
    current = list;
    while (current->next != NULL && current->next->accountno < newRecord.accountno) {
        current = current->next;
    }
    newRecord->next = current->next;
    current->next = newRecord;
}
