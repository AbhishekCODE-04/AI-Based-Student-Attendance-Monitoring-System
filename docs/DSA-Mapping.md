# DSA Concepts Mapping

This document explains the application of DSA-II concepts in the
AI-Based Student Attendance Monitoring System.

## 1. DSA Concepts Used / Proposed

| Unit / Module | DSA Concept | Application / Purpose |
|---|---|---|
| Unit 1 – Trees | BST | Efficient searching of student attendance records |
| Unit 1 – Trees | AVL Tree | Balanced and efficient attendance record searching |
| Unit 1 – Trees | Heap / Max Heap | Prioritizing students with low attendance or high risk |
| Unit 1 – Trees | Tree Traversal | Systematic processing of attendance records |
| Unit 2 – Graphs | Graph | Representing relationships between students and subjects |
| Unit 2 – Graphs | Adjacency List / Matrix | Storing student-subject connections efficiently |
| Unit 2 – Graphs | BFS / DFS | Traversing and analyzing student-subject relationships |

---

# 2. DSA Concepts Not Used Directly

Not every DSA concept is required for the current core functionality of
the project. The following concepts are not directly used because they
do not provide a significant advantage for the current requirements.

## Binary Tree

**Status:** Not used directly.

**Reason:**  
A general Binary Tree does not maintain an ordering property for
efficient searching. BST and AVL Tree are more suitable for organized
attendance-record searching.

---

## Linked List

**Status:** Not used directly.

**Reason:**  
A linked list mainly provides sequential access. The project requires
efficient searching and relationship analysis, for which BST and AVL
Tree are more suitable.

---

## Stack

**Status:** Not used directly.

**Reason:**  
The current attendance monitoring system does not require a
Last-In-First-Out (LIFO) operation as part of its core functionality.

---

## Queue

**Status:** Not used directly.

**Reason:**  
The current system does not require a First-In-First-Out (FIFO)
process as a core attendance operation.

---

## Hashing

**Status:** Not used directly.

**Reason:**  
Hashing could provide fast Student ID lookup, but the current project
focuses on applying tree and graph concepts from DSA-II. Therefore,
BST and AVL Tree are used for the proposed attendance-record searching.

---

## Min Heap

**Status:** Not used directly.

**Reason:**  
The proposed system focuses on prioritizing students using an
attendance or risk score. A Max Heap can be used when a higher risk
score represents a higher priority. A Min Heap could be incorporated
in a future version if the priority is based directly on the lowest
attendance percentage.

---

# 3. Reason for Selective DSA Usage

Different data structures are suitable for different operations.
Therefore, only the concepts that directly support the requirements of
the attendance monitoring system are selected.

### Main requirements and DSA mapping

- **BST** → Efficient searching of attendance records
- **AVL Tree** → Balanced searching
- **Heap** → Prioritizing students based on attendance/risk
- **Tree Traversal** → Systematic processing of records
- **Graph** → Representing student-subject relationships
- **Adjacency List / Matrix** → Storing graph relationships
- **BFS / DFS** → Traversing student-subject relationships

Other concepts may be incorporated in future versions if additional
system requirements are introduced.

---

# 4. Future Scope

The currently unused DSA concepts can be incorporated if the project
is expanded.

- **Hashing** → Fast Student ID lookup
- **Queue** → Sequential processing of attendance events
- **Stack** → Undo/history operations
- **Linked List** → Maintaining chronological attendance records
- **Min Heap** → Prioritizing students with the lowest attendance
