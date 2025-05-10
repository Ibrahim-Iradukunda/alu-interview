# 📄 Minimum Operations

## 📚 Description

This project provides a solution to the problem of finding the minimum number of operations required to get exactly `n` characters **H** in a text file using only **Copy All** and **Paste** operations. Starting with one character `H`, the goal is to determine the most efficient way to reach `n` Hs using these two operations.

---

## 📌 Requirements

- **Editor:** `vi`, `vim`, or `emacs`
- **Operating System:** Ubuntu 14.04 LTS
- **Python Version:** Python 3.4.3
- **Coding Standards:**
  - Files must end with a new line.
  - The first line of each file must be: `#!/usr/bin/python3`
  - All files must be executable.
  - Must follow **PEP 8** style guide (version 1.7.x).
  - Code must be properly documented.

---

## ⚙️ Function Prototype

```python
def minOperations(n):
    """
    Calculates the fewest number of operations to result in exactly n H characters.
    Args:
        n (int): Target number of H characters.
    Returns:
        int: Minimum number of operations or 0 if impossible.
    """

