# Emerging Technologies

## Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or Jupyter Lab

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd emerging-technologies
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

This will install:
- **numpy**: Numerical computing
- **qiskit**: Quantum computing framework
- **matplotlib**: Data visualization

## Running the Notebook

### Option 1: Using Jupyter Lab (Recommended)

```bash
jupyter lab problems.ipynb
```

This opens an interactive environment where you can:
- View and edit all cells
- Execute cells individually with Shift+Enter
- See output displayed inline

### Option 2: Using Classic Jupyter Notebook

```bash
jupyter notebook problems.ipynb
```

### Option 3: VSCode with Jupyter Extension

If using VSCode with the Jupyter extension installed:
1. Open `problems.ipynb` in VSCode
2. Click "Run All" or run individual cells with the run button

## Project Structure

The notebook is organized into 5 problems:

1. **Problem 1: Generating Random Boolean Functions** 
2. **Problem 2: Classical Testing for Function Type** 
3. **Problem 3: Quantum Oracles** 
4. **Problem 4: Deutsch's Algorithm** 
5. **Problem 5: Deutsch-Jozsa Algorithm** 

## Running Individual Cells

To execute a specific cell:
1. Click on the cell to select it
2. Press `Shift + Enter` to run it
3. Output will appear below the cell

## Tips

- Run cells in order from top to bottom
- Problem 1 must be completed before Problems 2+
- Each problem builds on previous concepts
- Use `print()` statements to debug and understand function behavior