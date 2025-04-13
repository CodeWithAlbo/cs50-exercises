# 🧠 Week 0 – Algorithms & Big-O Notation

## ✍️ What I Understood

David Malan showed that programming isn't just about getting something to work — it's about doing it *better*.  
Even with a simple problem (like finding a name in a phone book), there are *many* ways to approach it.  
Some are brute-force (slow), others are smart (fast).

And that's where **algorithms** come in: a series of steps to solve a problem efficiently.

---

## 📖 Key Concepts

- **Algorithm:** Step-by-step method to solve a problem.
- There’s more than one solution to a problem — but not all solutions are equal.
- Some are slower (linear), others smarter (logarithmic).

---

## 📊 Example: Searching a phonebook

| Approach                  | Description                                 | Time Complexity |
|---------------------------|---------------------------------------------|-----------------|
| Start from page 1 → end   | Check every page until you find the name    | O(n)            |
| Check two pages at once   | Same logic, but double speed                | O(n/2) ≈ O(n)   |
| Go to middle, divide      | Binary search (divide and conquer)          | O(log n)        |

---

## 📉 Visual Comparison

> As the size of the problem increases, the time difference between algorithms becomes huge.

- 🟥 **O(n)** → Linear (slow)
- 🟨 **O(n/2)** → Still linear, just a bit faster
- 🟩 **O(log n)** → Smart search: Double the size, only 1 extra step!

---

_“Programmers translate text-based, human instructions into code.”_  
_— David J. Malan_
