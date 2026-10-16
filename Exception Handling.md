# 🐍 Python Exception Handling

<br><br>

## 📌 Exception

- A runtime error that interrupts the normal flow of execution of a program.
- Every exception in Python is represented by a class.

### 🔹 Examples of Exceptions
- `ZeroDivisionError`
- `TypeError`
- `ValueError`
- `KeyError`
- `IndexError`
- `KeyboardInterrupt`

<br><br>

## 🛡️ Exception Handling

- A mechanism by which we can handle exceptions in Python.
- We can use the following blocks to handle different exception scenarios:

1. `try` block
2. `except` block
3. `else` block
4. `finally` block

<br><br>

## 🔹 Try Block

- A block of code that might raise an exception must be written inside the `try` block.

## 🔹 Except Block

- A block of code that executes when a specific exception occurs must be written inside the `except` block.

## 🔹 Else Block

- A block of code that executes only when no exception occurs in the `try` block.

## 🔹 Finally Block

- A block of code that executes whether an exception occurs or not.
- This block is generally used for cleanup operations.

<br><br>

## ⚡ Raise Keyword

- Using raise keyword, we can manually trigger any exceptions.
- We can trigger either built-in exception or custom exception.

---

### 📝 Syntax :

```python
raise exception_class_name()
```

or

```python
raise exception_class_name("message")
```

<br><br>

## 🧩 Custom Exception (User Defined Exception)

- An exception made by user for a specific purpose or scenario.

---

### 📝 Syntax :

```python
class UserExectionClassName(Exception):
      pass
```
