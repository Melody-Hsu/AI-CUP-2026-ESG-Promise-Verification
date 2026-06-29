# AI CUP 2026 ESG Promise Verification

This repository contains the source code for our solution to the AI CUP 2026 ESG Promise Verification Competition.

---

## Environment

- Python 3.x
- Google Colab
- NVIDIA A100 GPU
- PyTorch
- Hugging Face Transformers
- Pandas
- NumPy
- Scikit-learn

---

## Repository Structure

AI-CUP-2026-ESG-Promise-Verification/

├── AI_CUP_2026_ESG_Promise_Verification_Final.ipynb

├── README.md

└── requirements.txt

---

## Required Files

Before running the notebook, please prepare the following official competition files.

Required files:

- vpesg4k_train_1000.json
- vpesg4k_val_1000.csv
- vpesg4k_test_2000.csv
- submission_threshold.csv

---

## Google Colab Instructions

Before executing the notebook:

1. Open Google Colab.
2. Upload the notebook.
3. Upload all required dataset files listed above.
4. Upload the trained model weights (.pt files) if inference is required.
5. Execute the notebook from the first cell.

⚠️ The notebook requires all official dataset files to be uploaded before execution.
Otherwise, FileNotFoundError will occur.

---

## Model

- Pretrained Model: bert-base-chinese
- Framework: PyTorch
- Architecture:
  - BERT Encoder
  - CLS + Mean Pooling
  - Multi-task Learning
  - 4 Classification Heads
  - 5-Fold Weighted Ensemble

---

## Output

The notebook generates:

- submission.csv

---

## Competition

AI CUP 2026 ESG Promise Verification Competition

Official Website:

https://veripromiseesg.github.io/

---

## Author

Melody Hsu
