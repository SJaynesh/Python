# 📘 Python Modules & Packages


<br><br>

---

## 📦 Module

- A simple Python script (`.py`) which includes some functionalities like constants, functions and classes.
- This script is intended to be imported in another Python file, and then those functionalities are going to be used.

<br><br>

### 📝 Syntax

```python
import module_name

# OR

import module_name as alias_name

# OR

from module_name import functionality
```

<br><br>

### 📌 Types of Module

1. **Built-in Modules** (System Defined Modules)
2. **User-Defined Modules** (Custom Modules)

---

<br><br>

## 🏷️ `__name__` with `__main__`

- **Dunder Name:** `__name__`
- **Dunder Main:** `__main__`

- `__name__` is a globally available property in Python, which returns the following possible values:

<br>

  1. `__main__`
  2. `module_name`

- When we print the value of `__name__` by running the current file, it gives `__main__` as an output.
- When we print the value of `__name__` by running a different file where the module is imported, it gives `"module_name"` as an output.

---

<br><br>

## 🧩 Package

- A directory which consists one or more modules.
- A package can also contains `__init__` file
- When we import a package, a subpackage called `__pycache__` is automatically created. In that `__pycache__` subpackage, a byte code is consists.
- When our package is imported, a `__init__.py` file is automatically invoked.


<br><br>

### 📝 Syntax

```python
from package_name import module_name

or

from package_name import *
```

<br><br>


## 🧩 Higher-Order Functions

- A function which takes another function as an argument is known as a **Higher-Order Function**.
- Below are the most commonly used functions:

  - `sorted()`
  - `map()`
  - `filter()`
  - `reduce()`

---

### 🚀 Happy Coding! 🐍

