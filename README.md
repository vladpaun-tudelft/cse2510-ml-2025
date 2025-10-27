# CSE2510 — Machine Learning (2024)

> **Archived repository**  
> Personal archive of my TU Delft CSE2510 coursework. This repo is not maintained and is kept for reference only.

## Structure
- `Lab 1 – Introduction` … NumPy and Python warm-ups (Titanic CSV)
- `Lab 2 – Parametric` … Gaussian models and parametric classifiers
- `Lab 3 – Nonparametric` … kNN and kernel ideas
- `Lab 4 – Linear` … linear classifiers
- `Lab 5 – Fairness` … fairness metrics using a credit card CSV
- `Lab 6 – Nonlinear` … decision trees and more (`heart_disease.npy`)
- `Lab 7 – Unsupervised` … clustering and PCA (TIDIGITS audio not in repo by default)

## Getting started
1. Create an environment (pick one):
   ```bash
   python -m venv .venv && source .venv/bin/activate     # macOS or Linux
   # or: py -3 -m venv .venv && .venv\Scripts\activate # Windows
   ```
2. Install dependencies (typical stack):
   ```bash
   pip install numpy pandas matplotlib scikit-learn jupyter
   # for audio labs optional:
   pip install librosa soundfile
   ```
3. Launch notebooks:
   ```bash
   jupyter notebook
   ```

### Data
- Small CSV and NPY files are included.
- Large audio assets (`*.flac` for TIDIGITS) are ignored to keep the repo light.
  - If needed, place them under `Lab 7 - unsupervised/data/tidigits/` locally.
  - Prefer Git LFS if you must track them.

## Notes
- Consider `nbstripout` to remove notebook outputs on commit:
  ```bash
  pip install nbstripout
  nbstripout --install
  ```
