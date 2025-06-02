# Spam Detection NLP Project

This project implements a spam detection system using Natural Language Processing (NLP) and machine learning techniques in Python. The code is provided in a Jupyter notebook.

## Prerequisites

- Python 3.8 or higher
- Jupyter Notebook

### Required Python Packages (Install after reading "How to Run" section below)

Install all dependencies using:
pip install -r requirements.txt

Or, install manually:
pip install numpy pandas scikit-learn nltk jupyter

## Data

Place your training and test CSV files in a folder named `data`:
- `data/spam_detection_training_data.csv`
- `data/spam_detection_test_data.csv`

## How to Run

1. Activate your virtual environment (if using one):
   ``` 
   python -m venv venv
   ```
   ``` 
   venv\Scripts\activate  # On Windows
   ```
   or 
   ``` 
   source venv/bin/activate  # On macOS/Linux  
   ```
3. Install requirements:
   ```
   pip install -r requirements.txt
   ```
4. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```

5. Open the notebook (e.g., `spam_detection_nlp.ipynb`) on jupyter and run all cells.

## Output

The notebook will generate a CSV file with predictions (e.g., `results_task1.csv`) in your working directory.

## Project Structure

```
.
├── data/
│   ├── spam_detection_training_data.csv
│   └── spam_detection_test_data.csv
├── results/
│   └── results_task1.csv
├── spam_detection_nlp.ipynb
├── requirements.txt
└── README.md
```

## Notes

- Do **not** upload the `venv` folder or `.ipynb_checkpoints` to GitHub.
- For any issues, please open an issue in this repository.
