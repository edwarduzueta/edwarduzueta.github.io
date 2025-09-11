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
What started as a simple linked list assignment eventually grew into a larger project that pushed me to think about memory management, data persistence, and program design in a much deeper way.  

<div class="text-center p-3">
  <img src="../img/databas.png" alt="Database Screenshot" width="400px" class="img-thumbnail">
</div>

For the C version, I implemented functions such as `addRecord`, `printAllRecords`, `findRecord`, and `deleteRecord`.  
Each function had to carefully manage dynamic memory while still maintaining the linked list’s sorted order.  
In the C++ version, I encapsulated this logic inside a custom `llist` class, which required me to think in terms of **object-oriented design** rather than procedural programming.  
This shift forced me to reconsider how data and functionality should be structured, and I gained experience with constructors, destructors, and proper encapsulation of functionality.  

One of the most challenging aspects was ensuring that the program handled memory safely and avoided leaks.  
I also had to design insertion logic that would correctly place new records into their sorted position without disrupting the rest of the list.  
Building **file I/O** support added another layer of difficulty, since I needed to make sure that records were written to a file and restored properly between runs.  
Altogether, this project gave me valuable experience with debugging, testing, and transitioning code between languages and paradigms.  

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
