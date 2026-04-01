# IDS_supervised

Supervised Intrusion Detection System (IDS) project built in Python using network traffic features and machine learning models for binary attack/benign classification.

## Project Files

- `IDS_supervised.ipynb` - end-to-end notebook (preprocessing, model training, evaluation, visualizations).
- `dataset.csv` - project dataset (tracked with Git LFS because it is large).
- `docs/DRDO_IDS_Complete_Report.pdf` - complete project report document.

## Models Used

- Decision Tree
- Random Forest
- XGBoost
- Neural Network (MLP)
- Ensemble combinations

## Evaluation

The notebook evaluates model performance with:

- Accuracy
- Precision / Recall / F1-score
- Comparative plots for model behavior and training characteristics

## Quick Start

1. Clone the repository:
   `git clone https://github.com/sreenidhi2545/IDS_supervised.git`
2. Enter the project:
   `cd IDS_supervised`
3. Install Git LFS and pull dataset files:
   `git lfs install`
   `git lfs pull`
4. Install Python dependencies (example):
   `pip install pandas numpy scikit-learn matplotlib seaborn xgboost imbalanced-learn jupyter`
5. Run:
   `jupyter notebook IDS_supervised.ipynb`

## Notes

- `dataset.csv` is a large file (about 1.1 GB), so Git LFS is required to clone/download it correctly.
- The full write-up for this project is available in `docs/DRDO_IDS_Complete_Report.pdf`.
