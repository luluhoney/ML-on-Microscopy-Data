# ML on Microscopy Data

This project explores the application of machine learning to microscopy data, specifically focusing on multiclass classification using softmax regression and gradient descent optimization.

## Overview

The project builds fundamental machine learning components from scratch and applies them to:
- Synthetic data for validation and optimization exploration
- Real spectromicroscopy data for chromium compound classification

Key topics covered:
- Softmax regression for multiclass classification
- Cross-entropy loss function
- Gradient descent with early stopping
- Principal Component Analysis (PCA) for dimensionality reduction
- Confusion matrix analysis

## Requirements

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/luluhoney/ML-on-Microscopy-Data.git
   cd ML-on-Microscopy-Data
   ```

2. (Recommended) Create a virtual environment:
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:
   - **Windows (Command Prompt):**
     ```bash
     venv\Scripts\activate.bat
     ```
   - **Windows (PowerShell):**
     ```bash
     venv\Scripts\Activate.ps1
     ```
     If you get a permissions error in PowerShell, run:
     ```powershell
     Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
     ```
     Then try activating again.
   - **macOS/Linux:**
     ```bash
     source venv/bin/activate
     ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open `ML-on-Microscopy.ipynb`

3. Run all cells sequentially (Kernel → Run All) or execute cells individually

## Project Structure

```
ML-on-Microscopy-Data/
├── ML-on-Microscopy.ipynb     # Main Jupyter notebook
├── README.md                  # This file
├── requirements.txt           # Python dependencies
└── Data.npz                   # Real microscopy data
```

## Dependencies

| Package | Description |
|---------|-------------|
| numpy | Numerical computing and array operations |
| matplotlib | Plotting and visualisation |
| scikit-learn | Confusion matrix for performance evaluation |

## License

MIT License