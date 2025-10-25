# Linear Classifier Demo

Short description
This repository contains a small demo showing a random linear classifier applied to synthetic "dogs vs cats" feature data (whisker length and ear flappiness). The project includes a Jupyter notebook (sample.ipynb) and a tiny script (hellow.py).

Files
- sample.ipynb — notebook that generates synthetic data, plots it, implements a random linear classifier, and plots the decision boundary.
- hellow.py — simple test script (prints "Hello, world!").
- README.md — this file.

Requirements
- Python 3.14 (or 3.x)
- numpy
- matplotlib
- jupyter / ipykernel (to run the notebook in VS Code)

Quick setup (Windows / PowerShell)
1. Create a virtual environment (optional but recommended)
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1

2. Install dependencies
   python -m pip install --upgrade pip
   python -m pip install numpy matplotlib jupyter ipykernel

3. (Optional) Register kernel so VS Code notebook can use this interpreter
   python -m ipykernel install --user --name python3.14 --display-name "Python 3.14"

Run
- Run the script:
  python hellow.py

- Open and run the notebook in VS Code or with Jupyter:
  jupyter notebook

Notes
- If VS Code shows the "Internal" kernel, reload the window and choose "Select Another Kernel..." → pick "Python 3.14" or start a Jupyter server using the interpreter above and connect VS Code to it.
- Replace the kernel/venv names if you use a different interpreter.