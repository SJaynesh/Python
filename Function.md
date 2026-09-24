# 🐍 Python Functions & Scope Masterclass

A comprehensive reference guide covering advanced function parameters, docstrings, anonymous functions, scope management, and multi-value returns in Python.

---

## 📑 Table of Contents
- [Types of Function Parameters](#-types-of-function-parameters)
- [Docstrings (Document Strings)](#-docstrings-document-strings)
- [Anonymous / Lambda Functions](#-anonymous--lambda-functions)
- [Global Keyword](#-global-keyword)
- [Returning Multiple Values](#-how-to-return-multiple-values-from-a-function)

---

## ⚙️ Types of Function Parameters

In Python, function parameters are used to receive values when a function is called. Python provides different types of function parameters that make functions flexible and reusable.

1. **Required Positional Arguments**
2. **Optional Arguments**
   * Arbitrary Arguments (`*args`)
   * Keyword Arguments
   * Arbitrary Keyword Arguments (`**kwargs`)
3. **Default Arguments**

---

## 📖 Docstring (Document String)

* Documentation for any object in Python, such as functions, classes, modules, or packages.

### How to Create a Docstring?
* A docstring must be written as a multi-line string on the very first line inside the function, class, module, or package.

### How to Access a Docstring?
* **i.** `__doc__` attribute (Dunder doc)
* **ii.** `help()` function

---

## ⚡ Anonymous / Lambda Function

* A function without a name is called an **anonymous function**.
* This function does not have a multi-line body.
* This function must return some value or expression.

### Syntax:
```python
lambda arguments: expression
```

## 🌐 Global Keyword

* Using the `global` keyword, we can access and modify a global variable inside a local scope.

## How to Return Multiple Values from a Function?

* You can return multiple values from a function using:
*    List
*    Tuple
*    Set
*    Dictionary
*    Class & Object
