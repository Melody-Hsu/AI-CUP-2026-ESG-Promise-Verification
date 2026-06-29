# AI CUP 2026 ESG Promise Verification

This repository contains the source code for our solution to the **AI CUP 2026 ESG Promise Verification Competition**.

---

# Environment

- Platform: Google Colab
- Operating System: Linux (Google Colab)
- Programming Language: Python
- Deep Learning Framework: PyTorch
- Pretrained Model: bert-base-chinese
- Libraries:
  - transformers
  - pandas
  - numpy
  - scikit-learn
  - tqdm

---

# Repository

```
AI-CUP-2026-ESG-Promise-Verification/

├── AI_CUP_2026_ESG_Promise_Verification_Final.ipynb
├── README.md
└── .gitignore
```

---

# Required Files

This notebook requires the **official AI CUP 2026 VeriPromiseESG competition dataset**.

Please download the official dataset from the competition website before running this notebook.

Required files:

- vpesg4k_train_1000.json
- vpesg4k_test_2000.json
- vpesg4k_val_1000.csv
- vpesg4k_test_2000.csv


> **Note**
>
> The official competition dataset is **NOT included** in this repository.
>
> Please follow the competition regulations regarding dataset usage and distribution.

---

# How to Run

1. Open Google Colab.
2. Upload **AI_CUP_2026_ESG_Promise_Verification_Final.ipynb**.
3. Upload the required official dataset files listed above into the current Colab session.
4. Run all cells from the beginning.

---

# Model

- bert-base-chinese
- CLS + Mean Pooling
- Multi-task Learning
- Four Classification Heads
- Weighted Focal Loss
- 5-Fold Cross Validation
- Weighted Ensemble

---

# Input

Official AI CUP ESG dataset

Input files:

- vpesg4k_train_1000.json
- vpesg4k_val_1000.csv
- vpesg4k_test_2000.csv

---

# Output

The notebook generates:

- submission.csv

---

# Competition

AI CUP 2026 ESG Promise Verification Competition

Official Website:

https://veripromiseesg.github.io/

---

# Author

Melody Hsu
