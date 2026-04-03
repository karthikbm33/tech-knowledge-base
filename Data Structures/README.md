# 🚀 Data Structures & Algorithms Guide

<p align="center">
  <img src="https://img.shields.io/badge/Data%20Structures-Complete-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Algorithms-Reference-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Level-Beginner%20to%20Advanced-orange?style=for-the-badge">
</p>

---

## 📚 Reference
🔗 [Dictionary of Algorithms and Data Structures](https://xlinux.nist.gov/dads/)

---

# 📦 Data Structures

---

## 🧱 Arrays

| ⚙️ Operation              | ⏱️ Time Complexity |
|--------------------------|------------------|
| Access                   | Θ(1)             |
| Insert/Delete (Start)    | N/A              |
| Insert/Delete (End)      | N/A              |
| Insert/Delete (Middle)   | N/A              |
| Wasted Space             | 0                |

---

## 🔄 Dynamic Arrays

| ⚙️ Operation              | ⏱️ Time Complexity |
|--------------------------|------------------|
| Access                   | Θ(1)             |
| Insert/Delete (Start)    | Θ(n)             |
| Insert/Delete (End)      | Θ(1) *(amortized)* |
| Insert/Delete (Middle)   | Θ(n)             |
| Wasted Space             | Θ(n)             |

---

## 🔗 Linked Lists

🔍 Visualizations:  
- [Linked List](http://visualgo.net/list)  
- [Cycle Detection](http://visualgo.net/cyclefinding)

| ⚙️ Operation              | ⏱️ Time Complexity |
|--------------------------|------------------|
| Access                   | Θ(n)             |
| Insert/Delete (Start)    | Θ(1)             |
| Insert/Delete (End)      | Θ(1)             |
| Insert/Delete (Middle)   | Search + Θ(1)    |
| Wasted Space             | Θ(n)             |

---

## ⛰️ Binary Heaps

🔍 [Heap Visualization](http://visualgo.net/heap)

✔️ Fast min/max retrieval  
✔️ Used in Heap Sort  

| ⚙️ Operation | ⏱️ Time Complexity |
|-------------|------------------|
| Find Min    | Θ(1)             |
| Delete Min  | Θ(log n)         |
| Insert      | Θ(log n)         |
| Decrease Key| Θ(log n)         |
| Merge       | Θ(n)             |

---

## 📚 Stacks (LIFO)

🔍 [Visualization](https://www.cs.usfca.edu/~galles/visualization/StackArray.html)

- Last In, First Out  
- Operations: `push`, `pop`  
- Example: Reversing a word  

---

## 🚶 Queues (FIFO)

🔍 [Visualization](http://www.cs.usfca.edu/~galles/JavascriptVisual/QueueArray.html)

- First In, First Out  
- Operations: `enqueue`, `dequeue`  
- Example: Waiting systems  

---

## 🌳 Trees

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f7/Binary_tree.svg/300px-Binary_tree.svg.png">
</p>

- Hierarchical structure  
- Root + children nodes  

---

## 🌿 Binary Trees

🔍 [Visualization](http://kanaka.github.io/rbt_cfs/trees.html)

- Can be stored in arrays  
- Inefficient for sparse trees  

---

## 🌲 N-ary Trees

🔍 [Wikipedia](https://en.wikipedia.org/wiki/K-ary_tree)

- Max children = N  
- Binary tree → special case (N = 2)

---

## 🔍 Binary Search Trees (BST)

🔍 [Visualization](http://visualgo.net/bst)

| Operation | Average  | Worst Case |
|----------|----------|------------|
| Search   | O(log n) | O(n)       |
| Insert   | O(log n) | O(n)       |
| Delete   | O(log n) | O(n)       |
| Space    | O(log n) | O(n)       |

---

## ⚖️ Balanced Trees

- AVL Tree  
- Red-Black Tree  
- Splay Tree  

---

## 📍 K-d Trees

🔍 [Wikipedia](https://en.wikipedia.org/wiki/K-d_tree)

- Used for spatial data  
- Fast nearest neighbor search  

---

## 🔤 Trie (Prefix Tree)

🔍 [Visualization](https://people.ok.ubc.ca/ylucet/DS/Trie.html)

- Efficient prefix searching  
- Used in dictionaries & autocomplete  

---

## 🕸️ Graphs

🔍 [Visualization](http://visualgo.net/graphds)

### Types:
- Adjacency List → Sparse graphs  
- Adjacency Matrix → Dense graphs  

---

## 🧮 Hash Tables

🔍 [Visualization](http://visualgo.net/hashtable)

| Operation | Average | Worst Case |
|----------|--------|------------|
| Search   | O(1)  | O(n)       |
| Insert   | O(1)  | O(n)       |
| Delete   | O(1)  | O(n)       |
| Space    | O(n)  | O(n)       |

---

## 🔗 Union-Find (Disjoint Set)

🔍 [Visualization](http://visualgo.net/ufds)

- Fast connectivity checks  
- Near constant time: **O(α(n))**

---

## ⭐ Final Notes

✨ Covers essential Data Structures  
✨ Includes visual learning resources  
✨ Beginner → Advanced friendly  

---

<p align="center">
  💡 Keep Learning • Keep Building • Keep Growing 🚀
</p>
