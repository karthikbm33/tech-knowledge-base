# 🖥️ Operating Systems

<p align="center">
  <img src="https://img.shields.io/badge/Subject-Operating%20Systems-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Level-Intermediate-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Resources-Notes%20%7C%20Books%20%7C%20Papers-orange?style=for-the-badge">
</p>

---

## 📚 Course Notes

### 🎓 Udacity – Introduction to Operating Systems  
🔗 [Course Homepage](https://www.udacity.com/course/introduction-to-operating-systems--ud923)

- 📌 [Course Overview](https://docs.google.com/document/d/1NHgibsFIYxuzP6F-MUfdp7960ryAcPkuZmwCSgiys5A/pub)  
- 📌 [OS Introduction](https://docs.google.com/document/d/1ArRpNXkm4q2-OBP9RWjT5LhYdC0TwLwKnUqSNhL9JVE/pub)  
- 📌 [Processes & Process Management](https://docs.google.com/document/d/1egz8qH27XD6c4QYzd9akeO_0e-AvlCjzLkfZQfsn_nE/pub)  
- 📌 [Threads & Concurrency](https://docs.google.com/document/d/1LKAnbB42pv-bpr3QhqHgELdGkE7FUwSSWSozAP4DoDo/pub)  

---

## 📖 Recommended Books

- 📘 *Operating System Concepts*  
- 📘 *Operating System Concepts: Essentials*  
- 📘 *Modern Operating Systems*  
- 📘 [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/) *(Free)*  

---

## 🧠 Vocabulary

- 🔗 [OS Flashcards](https://quizlet.com/9875856/operating-system-concepts-ch-1-flash-cards/)

---

## 📄 Research Papers

- 📑 [Programming with Threads](https://s3.amazonaws.com/content.udacity-data.com/courses/ud923/references/ud923-birrell-paper.pdf)

---

## 📰 Articles

- 🧩 [Grok the GIL – Thread-safe Python](https://opensource.com/article/17/4/grok-gil)

---

## ⚙️ System Calls

> A system call is the programmatic way a program requests services from the OS kernel.

- Interface between **user programs ↔ OS kernel**
- Used for:
  - File access
  - Process creation
  - Hardware interaction  

💡 On x86:
- Uses `int` instruction  
- Linux: `int 0x80`  

---

## 🧵 Processes vs Threads

| Feature | Process | Thread |
|--------|--------|--------|
| Definition | Program in execution | Smallest execution unit |
| Memory | Separate | Shared |
| Communication | IPC required | Direct |
| Speed | Slower | Faster |

---

## 🔗 IPC (Interprocess Communication)

📎 [Learn IPC](http://advancedlinuxprogramming.com/alp-folder/alp-ch05-ipc.pdf)

---

## ⚡ Concurrency

> Multiple computations happening at the same time.

### ✅ Advantages
- Faster performance  
- Better resource utilization  

### ⚠️ Challenges
- Race conditions  
- Debugging complexity  

---

## 🔒 Synchronization Primitives

### 🔐 Locks / Mutex

- Ensures **mutual exclusion**
- Only one thread accesses resource at a time  

📎 [Locks Guide](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf)

---

### 🚦 Semaphores

- Controls access using a **counter**
- Types:
  - Binary (Mutex)
  - Counting  

---

### 🧠 Monitors

- Combines:
  - Mutual exclusion  
  - Condition waiting  

📎 [Monitor Concept](https://en.wikipedia.org/wiki/Monitor_(synchronization))

---

## ⚠️ Deadlock vs Livelock

### 🔴 Deadlock

<p align="center">
  <img src="http://cse.csusb.edu/tongyu/courses/cs660/images/deadlock/lock.gif" width="300">
</p>

- Processes wait forever  
- Caused by circular dependencies  

### ✅ Prevention
- Same lock order  
- Deadlock detection  
- Resource allocation graphs  

---

### 🟡 Livelock

<p align="center">
  <img src="https://image.slidesharecdn.com/29-deadlocks-sp082-111116105142-phpapp02/95/deadlocks-in-operating-system-31-638.jpg" width="600">
</p>

- Processes keep changing state  
- No actual progress  

### ✅ Prevention
- Random delays  
- Backoff strategies  

---

## 🧩 Key Takeaways

- OS manages **processes, memory, and hardware**
- Concurrency improves performance but adds complexity
- Synchronization is critical to avoid bugs
- Deadlocks & livelocks must be handled carefully

---

## ⭐ Contribute

Feel free to:
- Improve notes  
- Add resources  
- Fix errors  

---

## 📜 License

MIT License
