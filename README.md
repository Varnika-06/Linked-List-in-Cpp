# Experiment 17 – Linked List in C++

**Name:** Varnika Maurya  
**PRN:** 24070123160  

---

##  Objective
To study and implement the concept of **Linked Lists in C++** and perform basic operations such as:  
- Creating nodes and linking them  
- Inserting nodes at the front  
- Traversing and displaying nodes  

---

##  Theory
A **Linked List** is a linear data structure where elements (called **nodes**) are stored at non-contiguous memory locations. Each node contains:  
1. **Data field** → stores the value.  
2. **Pointer field (next)** → stores the address of the next node.  

Unlike arrays, linked lists are dynamic and can grow or shrink during runtime.  

**Advantages:**
- Dynamic memory allocation.  
- Efficient insertion and deletion operations.  

**Disadvantages:**
- Random access is not possible.  
- Requires extra memory for storing pointers.  

---

##  Program 1 – Creating and Displaying Linked Nodes

###  Algorithm:
1. Define a `Link` class with:  
   - `data` → integer field.  
   - `next` → pointer to next node.  
   - `display()` function → prints data and the next node’s data or `END`.  
2. In `main()`:  
   - Create two nodes `l1` and `l2`.  
   - Set `l1->next = l2`.  
   - Display both nodes using `display()`.  
3. End program.  

---

##  Program 2 – Adding Nodes to the Front of a Linked List

###  Algorithm:
1. Define a `Node` class with:  
   - `value` → integer field.  
   - `next` → pointer to next node.  
2. Define a function `addToFront(Node*& head, int val)` to:  
   - Create a new node with given value.  
   - Point its `next` to the current head.  
   - Update `head` to the new node.  
3. Define a function `printList(Node* head)` to traverse and display all nodes until `NULL`.  
4. In `main()`:  
   - Initialize `head = nullptr`.  
   - Call `addToFront()` multiple times to insert nodes.  
   - Call `printList()` after each insertion.  
5. End program.  

---

##  Conclusion
From this experiment, we learned:  
- The concept of **nodes** and **pointers** in linked lists.  
- How to **link nodes** manually and **traverse** them.  
- How to implement **insertion at the front** of a linked list.  
- Linked lists provide dynamic memory management but require pointer handling.  

---
