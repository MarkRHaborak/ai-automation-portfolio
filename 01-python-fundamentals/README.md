
# Python Fundamentals Learning Path

**Course:** Programming for Everybody (Getting Started with Python)  
**Platform:** Coursera (audit, free)  
**Duration:** Weeks 1–2 (30 hours target)  
**Status:** In Progress (currently Chapter 3: Conditional Code)

---

## Course Overview

Python is the foundation for everything: automation scripts, data analysis, API integration, and FinOPS tools. This folder documents my journey through the fundamentals.

**Why this course:**
- ✅ Free audit option (no paywall)
- ✅ Beginner-friendly + practical
- ✅ Covers core concepts needed for Projects 1 & 2
- ✅ Industry standard for learning Python basics

---

## Progress Tracking

### Completed
- [x] **Chapter 1: Getting Started**
  - Variables, data types, strings
  - Print statements, basic I/O
  
- [x] **Chapter 2: Variables and Expressions**
  - Assignment operators
  - Arithmetic operations
  - Type conversions (int, float, str)

### In Progress
- [ ] **Chapter 3: Conditional Code** (Current)
  - If/elif/else statements
  - Boolean logic
  - Comparison operators
  - Nested conditionals

### Coming Up
- [ ] **Chapter 4: Functions** (This week)
  - Defining functions
  - Parameters and return values
  - Scope and variable lifetime

- [ ] **Chapter 5: Loops** (This week)
  - For loops (iteration)
  - While loops (conditions)
  - Break and continue
  - Nested loops

---

## Key Concepts Learned

### Chapter 1–2: Variables & Expressions
```python
# Variables and types
name = "Mark"
age = 45
is_learning = True

# Arithmetic
total_cost = 500 + 150  # 650
discount = total_cost * 0.1  # 65
final_price = total_cost - discount  # 585

# String operations
greeting = "Hello, " + name
message = f"I am {age} years old"
```


### Chapter 3: Conditional Code (Currently Learning)

```python
# Basic if/elif/else
if age >= 18:
    print("Adult")
elif age >= 13:
    print("Teenager")
else:
    print("Child")

# Comparison operators
# ==, !=, <, >, <=, >=

# Boolean logic
if (age > 18) and (is_learning == True):
    print("Adult learner")

if (day == "Saturday") or (day == "Sunday"):
    print("Weekend")
```


---

## Why This Matters (For FinOPS)

**Project 1 (Cost Anomaly Detector) will require:**

- ✅ Variables to store cost data
- ✅ Conditionals to detect anomalies (if cost > threshold)
- ✅ Functions to organize logic
- ✅ Loops to process daily cost data

**Example from Project 1:**

```python
# Detect cost anomalies
if daily_cost > (average_cost + 2 * std_dev):
    print(f"Anomaly detected: ${daily_cost}")
    send_alert()
```


---

## Learning Goals

**By end of Week 2:**

- ✅ Complete all 5 chapters
- ✅ Understand control flow (if/elif, loops)
- ✅ Write basic functions
- ✅ Earn course certificate
- ✅ Build 2–3 practice scripts

---

## Practice Exercises

As I learn each chapter, I'll add practice scripts here:

- `chapter1_variables.py` - Variables and print statements
- `chapter2_expressions.py` - Arithmetic and type conversions
- `chapter3_conditionals.py` - If/elif/else logic
- `chapter4_functions.py` - Function definitions (coming)
- `chapter5_loops.py` - For/while loops (coming)

---

## Supplementary Resources

- **[Python Official Docs](https://docs.python.org/3/)**
- **[W3Schools Python Tutorial](https://www.w3schools.com/python/)**
- **[Real Python Articles](https://realpython.com/)** (for deeper dives)

---

## Weekly Milestones

| Week | Goal | Status |
| :-- | :-- | :-- |
| **Week 1 (Jan 1–5)** | Chapters 1–3 complete, conditionals mastered | 🟡 In Progress |
| **Week 2 (Jan 6–12)** | Chapters 4–5 complete, certificate earned | ⏳ Coming |


---

## Notes to Self

- Don't rush chapters—understanding is more important than speed
- Write extra practice scripts beyond course assignments
- Relate concepts to FinOPS problems (thinking like an analyst)
- Next: Functions will be the bridge to writing reusable automation code

---

*Last updated: January 1, 2026 (Chapter 3 in progress)*
*Next update: January 5, 2026 (Week 1 completion)*

```

***

## 📝 **How to Add This:**

1. **Open VS Code**
2. **Open:** `01-python-fundamentals/README.md`
3. **Paste the content above**
4. **Save** (Ctrl+S)
5. **Push to GitHub:**

```powershell
git add .
git commit -m "Add Python Fundamentals README with progress tracking"
git push origin main
```


***

**This README serves as:**

- ✅ **Progress tracker** (current chapter at a glance)
- ✅ **Learning notes** (key concepts documented)
- ✅ **Hiring manager proof** (shows learning discipline)
- ✅ **Your reference** (come back to it in Week 2)

