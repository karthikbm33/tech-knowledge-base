# 📐 Mathematics Knowledge Base

<p align="center">
  <b>A curated collection of essential mathematics concepts for computer science & problem solving</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Topics-Math-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Level-Beginner%20to%20Advanced-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Focus-CS%20Foundations-orange?style=for-the-badge">
</p>

---

## 🧮 Radix (Number Systems)

🔹 [Radix](https://en.wikipedia.org/wiki/Radix)

> In numeral systems, the **radix (base)** is the number of unique digits used to represent numbers.
> Example: Decimal system → Base 10 (digits 0–9)

🔹 [Base Conversion](https://en.wikipedia.org/wiki/Positional_notation#Base_conversion)
🔹 [Converting to/from Decimal](http://www.cs.trincoll.edu/~ram/cpsc110/inclass/conversions.html)

---

## 💻 Binary Representations

### 🔸 Sign-Magnitude

* Uses **1 bit for sign** and remaining for value
* `0 = positive`, `1 = negative`

---

### 🔸 One's Complement

* Flip all bits (0 ↔ 1)
* Represents negative numbers
  ⚠️ Issues:
* Two zeros (+0 and -0)
* Complex arithmetic

---

### 🔸 Two's Complement ⭐ (Most Important)

* Standard in modern computing
* Formula:

  ```
  2^N - number
  ```
* Eliminates negative zero
* Simplifies arithmetic operations

---

## 📊 Discrete Mathematics

* 📘 [Concrete Mathematics – Knuth](http://www.amazon.com/Concrete-Mathematics-Foundation-Computer-Science/dp/0201558025)
* 🎓 [MIT – Mathematics for CS](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/)
* 🏫 [University of Victoria Guide](http://www.math.uvic.ca/faculty/gmacgill/guide/index.html)

---

## ➕ Summation Formulas

```math
Σ(i = 1 → n) i = n(n + 1) / 2
```

* General:

```math
Σ i^k = O(n^{k+1})
```

---

## 📉 Logarithm Rules

* `log(mn) = log(m) + log(n)`
* `log(m/n) = log(m) - log(n)`

### ⚡ Fast Multiplication Trick

```math
mn = e^{ln(m) + ln(n)}
```

---

## 🔁 Recurrence Relations

* 📄 [Duke University Notes](https://users.cs.duke.edu/~reif/courses/alglectures/skiena.lectures/lecture3.pdf)
* 📄 [CMU Guide](http://www.cs.cmu.edu/~rweba/algf09/solverecurrencesSF.pdf)

---

## 🎲 Probability

* 📊 [Khan Academy](https://www.khanacademy.org/math/probability?t=table-of-contents)
* 🎓 [Udacity – Statistics](https://www.udacity.com/course/intro-to-statistics--st101)

---

## 🧩 Combinatorics

* 📘 [Khan Academy](https://www.khanacademy.org/math/probability/probability-and-combinatorics-topic)
* 📖 [Binomial Coefficient](https://en.wikipedia.org/wiki/Binomial_coefficient)
* 📖 [Combination](https://en.wikipedia.org/wiki/Combination)

### 🔹 Combinations

```math
^nC_r = \frac{n!}{r!(n-r)!}
```

* Number of ways to choose **r elements from n**

---

### 🔹 Permutations

```math
^nP_r = \frac{n!}{(n-r)!}
```

* Number of ways to arrange **r elements from n**

---

### 🔹 Subsets

```math
Total subsets = 2^n
```

---

## ✨ Why this repo?

✔️ Clean explanations
✔️ Useful for interviews & exams
✔️ Covers core CS math concepts
✔️ Beginner → Advanced friendly

---

## 🚀 Contribution

Want to improve this?

* Fork the repo
* Add content
* Create a pull request

---

## ⭐ Support

If you find this useful, consider giving it a ⭐ on GitHub!

---
