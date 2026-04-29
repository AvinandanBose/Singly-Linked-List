

# 📌 Singly Linked List

A detailed implementation and theoretical explanation of the **Singly Linked List**, covering node structure, memory allocation, pointer concepts, and fundamental operations. This repository combines conceptual understanding with program-based implementation for learning data structures effectively.

---

## 📖 Contents

### 🔹 1. Introduction

* A linked list is a collection of nodes
* Each node contains:

  * **Data field**
  * **Next pointer (link field)**
* Nodes are connected sequentially using pointers
* The last node points to **NULL**, indicating the end of the list 

---

### 🔹 2. Key Concepts

* **Head Pointer** → Points to the first node
* **Tail Node** → Last node (points to NULL)
* **Null List** → List with zero elements
* **Dynamic Memory Allocation** using `malloc()`
* Nodes are stored in **non-contiguous memory**

---

### 🔹 3. Node Structure (C/C++)

```c
typedef struct ListNode {
    int data;
    struct ListNode *next;
} Node;
```

* `data` → stores value
* `next` → stores address of next node

---

### 🔹 4. Creating an Empty List

```c
void createEmptyList(Node **head) {
    *head = nullptr;
}
```

* Uses **pointer to pointer (`Node **head`)**
* Initializes list as empty (`NULL`)
* Demonstrates **call by reference**

---

### 🔹 5. Important Concepts Explained

#### ✔️ Typedef

* Simplifies struct naming
* Example: `Node` instead of `struct ListNode`

#### ✔️ Global vs Local Head

* Global head is automatically initialized to NULL
* Local head must be explicitly initialized

#### ✔️ Zero Initialization Rule

* Global/static variables are initialized to **NULL (0)** by default 

---

### 🔹 6. Linked List Properties

* Linear data structure
* Sequential access only
* Dynamic size (not fixed)
* Efficient insertion and deletion
* Uses pointer-based linking

---

### 🔹 7. Array vs Linked List

| Feature            | Array                    | Linked List         |
| ------------------ | ------------------------ | ------------------- |
| Access             | Random access            | Sequential access   |
| Size               | Fixed                    | Dynamic             |
| Memory             | Contiguous               | Non-contiguous      |
| Insertion/Deletion | Costly (shifting needed) | Efficient           |
| Memory Usage       | May waste space          | Allocated on demand |

*(Derived from comparison table in the PDF)* 

---

## ⚙️ Features

* ✔️ Clear theoretical explanation
* ✔️ Node-based implementation
* ✔️ Pointer-to-pointer usage
* ✔️ Memory management concepts
* ✔️ Beginner-friendly structured notes

---

## 🚀 Getting Started

### 🔧 Requirements

* C / C++ Compiler (GCC / Clang)

### ▶️ Run the Program

```bash
gcc program.c -o sll
./sll
```

---

## 🧠 Learning Outcomes

After studying this repository, you will:

* Understand internal working of linked lists
* Learn pointer manipulation deeply
* Understand dynamic memory allocation
* Differentiate between arrays and linked lists
* Implement linked list from scratch

---

## 📌 Future Enhancements

* Insertion & Deletion implementations
* Circular Linked List
* Doubly Linked List
* Visualization of nodes

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Avinandan Bose**
- GitHub: [@AvinandanBose](https://github.com/AvinandanBose)
