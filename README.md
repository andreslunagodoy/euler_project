# Project Euler Solutions

This repository contains my solutions to [Project Euler](https://projecteuler.net/) problems using Python and Jupyter notebooks. It demonstrates skills in algorithmic problem solving, mathematics, and programming.

---

## Folder Structure

- `notebooks/` - Jupyter notebooks with problem statements and solutions, ten problems per notebook (`Euler_001010.ipynb` covers problems 1-10, and so on). `Euler_extras.ipynb` holds problems solved outside that sequence.
- `notebooks/files/` - Input data files used by some problems.
- `util/` - `euler_tools.py`, the helper functions (primes, digits, divisors, ...) imported by every notebook.
- `.gitignore` - Excludes temporary files like `__pycache__/`, `.ipynb_checkpoints/` and `.DS_Store`.

---

## About This Project

Project Euler provides challenging mathematical and computational problems. Solving them helped me:

- Improve Python programming skills.
- Develop efficient algorithms for number theory, combinatorics, and optimization problems.
- Practice analytical thinking and problem decomposition.

---

## How to Use

1. Clone this repository:

```bash
git clone https://github.com/andreslunagodoy/ProjectEuler.git
```

2. Open a notebook from inside the `notebooks/` folder (the notebooks use relative paths to `../util` and `files/`):

```bash
cd ProjectEuler/notebooks
jupyter notebook
```

Note: the first cell of each notebook imports `euler_tools`, which generates all primes under 10,000,000. This takes a little while the first time it runs.
