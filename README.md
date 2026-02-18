 📘 README — Star Pattern Program (Python)

## 📌 Description

This Python program prints a **left-side triangle star pattern** using nested loops.

It prints stars (`*`) line by line in increasing order.

---

## ⚙️ Code

```python
rows = 5

for i in range(1, rows + 1):
    for j in range(i):
        print("*", end="")
    print()
```

---

## 🧠 Simple Step-by-Step Explanation

### 1️⃣ Set number of rows

```python
rows = 5
```

This means the pattern will have **5 lines**.

---

### 2️⃣ Outer Loop (Controls Rows)

```python
for i in range(1, rows + 1):
```

This loop runs from **1 to 5**
It decides **how many lines** will print.

---

### 3️⃣ Inner Loop (Print Stars)

```python
for j in range(i):
```

This prints stars according to the row number.

👉 Row 1 → 1 star
👉 Row 2 → 2 stars
👉 Row 3 → 3 stars

and so on.

---

### 4️⃣ Print Stars in Same Line

```python
print("*", end="")
```

* `end=""` keeps printing stars in the **same line**
* Without it, stars would print on new lines.

---

### 5️⃣ Move to Next Line

```python
print()
```

This moves the cursor to the **next line** after each row.

---

## ▶️ Output

```
*
**
***
****
*****
```

---

## 🔑 Key Concepts Learned

* Nested loops
* Pattern printing logic
* `range()` function
* `end=""` usage

---

## 🚀 Real-World Importance

Pattern programs help you understand:

* Loop logic
* Problem solving
* Interview coding basics
---

## ⭐ Easy Trick to Remember

👉 Outer loop = **Rows**
👉 Inner loop = **Stars per row**
---

<img width="658" height="757" alt="image" src="https://github.com/user-attachments/assets/6868afbb-d7be-453d-8755-15e0876e9f95" />

