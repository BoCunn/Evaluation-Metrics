# Titanic Evaluation Script

Trains a Random Forest model on the Titanic dataset and evaluates it using confusion matrix, precision, recall, and F1 score.

## Requirements

```
pip install pandas scikit-learn matplotlib seaborn
```

## Folder Structure

```
Week6/
├── scripts/
│   └── titanic_evaluation.py
└── data/
    ├── train.csv
    ├── test.csv
    └── gender_submission.csv
```

## Usage

```
python titanic_evaluation.py
```

## Output

- Metrics printed to terminal
- `confusion_matrix.png` saved to the scripts folder