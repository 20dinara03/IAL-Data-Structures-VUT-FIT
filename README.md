# Data Structures in C (IAL Course)

This project implements **three fundamental data structures** as part of the **IAL (Algorithms)** course:
1. **Singly Linked List** (implemented in `c201.c`)
2. **Queue using an Array** (implemented in `c203.c`)
3. **Doubly Linked List** (implemented in `c206.c`)

Each structure is implemented with standard operations and accompanied by a **test suite** for validation.

## 📌 Project Overview
- **Language:** C
- **Concepts:** Linked List, Queue (Circular Buffer), Doubly Linked List
- **Key Features:**
  - **List initialization and disposal**
  - **Insertion and deletion of elements**
  - **Checking and setting values**
  - **Queue operations (enqueue, dequeue, front, etc.)**
  - **Doubly linked list traversal**
  - **Unit tests for all structures**

## 🏗️ Implemented Structures & Functions

### **1️⃣ Singly Linked List (`c201.c`)**
| Function | Description |
|----------|------------|
| `List_Init` | Initializes a linked list |
| `List_Dispose` | Deletes all elements from the list |
| `List_InsertFirst` | Inserts an element at the beginning |
| `List_First` | Sets the first element as active |
| `List_GetFirst` | Retrieves the value of the first element |
| `List_DeleteFirst` | Deletes the first element |
| `List_DeleteAfter` | Deletes an element after the active one |
| `List_InsertAfter` | Inserts an element after the active one |
| `List_GetValue` | Retrieves the value of the active element |
| `List_SetValue` | Updates the value of the active element |
| `List_Next` | Moves to the next element |
| `List_IsActive` | Checks if the list has an active element |

### **2️⃣ Queue using an Array (`c203.c`)**
| Function | Description |
|----------|------------|
| `Queue_Init` | Initializes the queue |
| `Queue_IsEmpty` | Checks if the queue is empty |
| `Queue_IsFull` | Checks if the queue is full |
| `Queue_Front` | Returns the front element without removing it |
| `Queue_Remove` | Removes the front element |
| `Queue_Dequeue` | Retrieves and removes the front element |
| `Queue_Enqueue` | Adds an element to the queue |

### **3️⃣ Doubly Linked List (`c206.c`)**
| Function | Description |
|----------|------------|
| `DLL_Init` | Initializes a doubly linked list |
| `DLL_Dispose` | Deletes all elements from the list |
| `DLL_InsertFirst` | Inserts an element at the beginning |
| `DLL_InsertLast` | Inserts an element at the end |
| `DLL_First` | Sets the first element as active |
| `DLL_Last` | Sets the last element as active |
| `DLL_GetFirst` | Retrieves the value of the first element |
| `DLL_GetLast` | Retrieves the value of the last element |
| `DLL_DeleteFirst` | Deletes the first element |
| `DLL_DeleteLast` | Deletes the last element |
| `DLL_DeleteAfter` | Deletes an element after the active one |
| `DLL_DeleteBefore` | Deletes an element before the active one |
| `DLL_InsertAfter` | Inserts an element after the active one |
| `DLL_InsertBefore` | Inserts an element before the active one |
| `DLL_GetValue` | Retrieves the value of the active element |
| `DLL_SetValue` | Updates the value of the active element |
| `DLL_Next` | Moves to the next element |
| `DLL_Previous` | Moves to the previous element |
| `DLL_IsActive` | Checks if the list has an active element |

## 📁 Project Files
### 🔹 **Singly Linked List (`c201`)**
- `c201.c` – Implementation of linked list operations
- `c201.h` – Header file defining the list structure and function prototypes
- `c201-test.c` – Test suite for linked list
- `c201-test-utils.c` – Utility functions for testing
- `c201-test-utils.h` – Header file for test utilities

### 🔹 **Queue (`c203`)**
- `c203.c` – Implementation of queue operations
- `c203.h` – Header file defining the queue structure and function prototypes
- `c203-test.c` – Test suite for queue
- `c203-test-utils.c` – Utility functions for testing
- `c203-test-utils.h` – Header file for test utilities

### 🔹 **Doubly Linked List (`c206`)**
- `c206.c` – Implementation of doubly linked list operations
- `c206.h` – Header file defining the list structure and function prototypes
- `c206-test.c` – Test suite for doubly linked list
- `c206-test-utils.c` – Utility functions for testing
- `c206-test-utils.h` – Header file for test utilities

### 🔹 **Build & Test**
- `Makefile` – Build script for compiling all structures and running tests

## 🚀 How to Build and Run
1. **Compile the project** using the provided `Makefile`:
   ```bash
   make
2. Run the singly linked list tests:
   ```bash
   ./c201-test
3. Run the queue tests:
   ```bash
   ./c203-test
4. Run the doubly linked list tests:
   ```bash
   ./c206-test
## 📝 Author
**Dinara Garipova**  
Project for **IAL Course**  

## ⚖️ License
This project is licensed under the **MIT License** – you are free to use, modify, and distribute with attribution.
