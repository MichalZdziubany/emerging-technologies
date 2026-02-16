# Emerging Technologies: Quantum Computing Assignment

## Overview

This assignment explores foundational concepts in quantum computing, particularly focusing on the Deutsch-Jozsa algorithm and quantum oracle implementations. The project demonstrates the application of classical Boolean functions and their quantum counterparts to understand quantum computational advantages.

## Table of Contents

1. [Problem Statements](#problem-statements)
2. [Setup & Installation](#setup--installation)
3. [Project Structure](#project-structure)
4. [Usage Guide](#usage-guide)
5. [Implementation Progress](#implementation-progress)
6. [Academic References](#academic-references)

## Setup & Installation

### Requirements

- Python 3.8 or higher
- Jupyter Notebook or Jupyter Lab

### Installation Steps

1. Clone the repository:
```bash
git clone <repository-url>
cd emerging-technologies
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

**Dependencies:**
- **numpy**: Numerical computing and array operations
- **qiskit**: IBM's quantum computing framework
- **matplotlib**: Data visualization

---

## Problem Statements

The assignment comprises five interconnected problems:

1. **Problem 1: Generating Random Boolean Functions**
   - Generate random Boolean functions with 4 inputs and 1 output
   - Types: Constant (returns same value for all inputs) or Balanced (returns 1 for exactly half the inputs)
   - Implementation uses closures and dictionary-based truth tables

2. **Problem 2: Classical Testing for Function Type**
   - Determine function type through classical queries
   - Test all 16 possible input combinations
   - Compare classical query complexity

3. **Problem 3: Quantum Oracles**

4. **Problem 4: Deutsch's Algorithm**

5. **Problem 5: Deutsch-Jozsa Algorithm**


## Project Structure

```
emerging-technologies/
├── problems.ipynb          # Main assignment notebook
├── requirements.txt        # Python dependencies
└── README.md              # This file
```

---

## Usage Guide

### Option 1: Jupyter Lab (Recommended)

```bash
jupyter lab problems.ipynb
```

### Option 2: Classic Jupyter Notebook

```bash
jupyter notebook problems.ipynb
```

### Option 3: VSCode with Jupyter Extension

1. Open `problems.ipynb` in VSCode
2. Use "Run All" or execute individual cells with the run button

### Execution Notes

- Execute cells sequentially from top to bottom
- Problem 1 must be completed before dependent problems
- Each problem builds on previous implementations
- Use print statements for debugging and verification

## References

- IBM Quantum Learning: [Classical Information & Operations](https://quantum.cloud.ibm.com/learning/)
- Python Closures: [Real Python - Closures](https://realpython.com/python-closures/)
- Python Lambda Functions: [Real Python - Lambda Functions](https://realpython.com/python-lambda/)
- Deutsch-Jozsa Algorithm: [Qiskit Textbook](https://qiskit.org/textbook)