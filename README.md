# Advanced Programming Lab (AP) 🚀

[![Made with Python](https://img.shields.io/badge/Python-3.11%2B-blue.svg)](https://www.python.org/) [![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg)](https://jupyter.org/) [![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](#)

Hands-on, Jupyter-first practice for Python fundamentals: I/O, arithmetic, swapping values, and simple branching.

## Highlights ✨
- Jupyter-native flow with instant feedback in each cell.
- Pure standard library; nothing to install beyond Python and Jupyter.
- Windows-friendly instructions and paths.

## What's Inside 📂
- `AP-LAB-1.ipynb` — Basic I/O, arithmetic operators, swapping, and conditionals.
- `AP-LAB-2.ipynb` — String operations, pattern printing.
- `AP-LAB-3.ipynb` — Functions, recursion, lists, dictionaries, and OOP basics.

## Lab Exercise Overview
- **AP-LAB-1**: `print()` greeting; integer prompts; arithmetic operators (add, subtract, multiply, float divide, modulus, floor divide, exponent); swap two numbers with a temp variable; even/odd check with a simple `if/else`.

- **AP-LAB-2**: String reversal using loops; count vowels, consonants, digits, and spaces in a string; palindrome checker; star patterns (ascending and descending triangles).

- **AP-LAB-3**: Factorial using loops; Fibonacci sequence generator; find largest element in a list; remove duplicates from a list; find second-largest element; character frequency counter using dictionaries; find key with maximum value in a dictionary; factorial function (iterative and recursive); basic OOP with `Student` class (name, roll number, branch).

## Quickstart (Windows) ⚡
1) **Requirements**: Python 3.11+ (and optionally Git).

2) **Create a virtual environment** (optional but recommended):
```powershell
cd "c:\\Users\\shriy\\Desktop\\AP LAB"
python -m venv .venv
\.venv\\Scripts\\activate
```

3) **Install Jupyter** (if needed):
```powershell
pip install --upgrade pip
pip install jupyter
```

4) **Launch the notebook**:
```powershell
jupyter lab
# or
jupyter notebook
```

## Recommended Workflow 🧭
- Run cells top-to-bottom initially to populate outputs.
- Provide integer inputs when prompted; validation is minimal.
- Restart the kernel and rerun all cells before sharing to ensure reproducibility.
- Duplicate the notebook for experiments (e.g., `AP-LAB1-play.ipynb`).

## Troubleshooting 🛠️
- Kernel cannot find Jupyter: activate the venv (`\.venv\\Scripts\\activate`) and ensure Jupyter is installed.
- Paths with spaces: keep them quoted in PowerShell (e.g., `"c:\\Users\\shriy\\Desktop\\AP LAB"`).
- Division tips: `/` is float division; `//` is floor (integer) division.

## Nice-to-Haves 🎯
- Add input validation for non-integer entries.
- Add brief markdown notes per exercise to outline intent and expected inputs.
- Capture sample runs (inputs/outputs) for quick reference.
