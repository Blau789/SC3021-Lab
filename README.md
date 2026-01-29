# Project Setup Guide

This project uses Python with Jupyter Notebook for data analysis and visualization.

## Prerequisites

- Python 3.13 or higher
- pip (Python package manager)

## Installation

### 1. Clone the repository
```bash
git clone <your-repository-url>
cd 3021
```

### 2. Create a virtual environment
```bash
python -m venv .venv
```

### 3. Activate the virtual environment

**On macOS/Linux:**
```bash
source .venv/bin/activate
```

**On Windows:**
```bash
.venv\Scripts\activate
```

### 4. Install required packages
```bash
pip install -r requirements.txt
```

## Installed Packages

This project uses the following main packages:
- **numpy** - Numerical computing library
- **pandas** - Data manipulation and analysis
- **matplotlib** - Data visualization
- **jupyter** - Jupyter notebook support
- **ipykernel** - Python kernel for Jupyter

## Running the Project

1. Make sure your virtual environment is activated
2. Open `Project.ipynb` in VS Code or Jupyter Notebook
3. Run the cells to execute the code

## VS Code Setup

If using VS Code:
1. Install the Python extension
2. Install the Jupyter extension
3. Select the `.venv` Python interpreter when prompted
4. Open `Project.ipynb` and start coding!

## Deactivating Virtual Environment

When you're done working:
```bash
deactivate
```

## Updating Dependencies

If you install new packages:
```bash
pip install <package-name>
pip freeze > requirements.txt
```

This updates the `requirements.txt` file for others to use.
