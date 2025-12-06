# Advanced Programming Lab (AP) \ud83d\ude80

[![Made with Python](https://img.shields.io/badge/Python-3.11%2B-blue.svg)](https://www.python.org/) [![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg)](https://jupyter.org/) [![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](#)

Hands-on notebook for practicing Python fundamentals: I/O, arithmetic, swapping values, and basic branching in a Jupyter-first workflow.

## Highlights \u2728
- Jupyter-native: mix code and outputs for quick feedback.
- Pure Python standard library; no third-party dependencies required.
- Windows-friendly commands and paths.

## What's Inside \ud83d\uddc2\ufe0f
- `AP-LAB1.ipynb`  Lab notebook (run top-to-bottom or cell-by-cell).

## Lab Exercise Overview
- **AP-LAB1**: `print()` greeting; integer input prompts; arithmetic operators (add, subtract, multiply, float divide, modulus, floor divide, exponent); swap two numbers using a temp variable; even/odd check with a simple `if/else`.

## Quickstart (Windows-friendly) \u26a1
1) **Requirements**: Python 3.11+, Git (optional).

2) **Create a virtual environment** (optional but recommended):
```powershell
cd "c:\\Users\\shriy\\Desktop\\AP LAB"
python -m venv .venv
\.venv\\Scripts\\activate
```

3) **Install Jupyter** (only if not already available):
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

## Recommended Workflow \ud83e\dded
- Run cells top-to-bottom the first time to populate outputs.
- Provide integer inputs when prompted; no validation is included.
- Restart kernel and rerun all cells before sharing to ensure outputs are reproducible.
- Duplicate the notebook for experiments if desired (e.g., `AP-LAB1-play.ipynb`).

## Troubleshooting \ud83d\dee1\ufe0f
- Kernel cannot find Jupyter: ensure the venv is activated (`\.venv\\Scripts\\activate`) and Jupyter is installed.
- Path issues: keep paths quoted in PowerShell when they include spaces (e.g., `"c:\\Users\\shriy\\Desktop\\AP LAB"`).
- Division: `/` performs float division; use `//` for floor (integer) division.

## Nice-to-Haves \ud83c\udfaf
- Add simple input validation to handle non-integer entries gracefully.
- Add docstrings or brief markdown cells describing each exercise and expected inputs.
- Capture sample runs (inputs/outputs) in the notebook for future reference.
