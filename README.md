# ECG Arrhythmia Classification using Machine Learning

## Description
Comparative study of 4 ML models (Logistic Regression, Random Forest, 
MLP, Transformer) for automatic classification of 5 cardiac arrhythmia 
types using the MIT-BIH Arrhythmia Database.

**Best model:** Random Forest — 95.6% accuracy

## Dataset
MIT-BIH Arrhythmia Database (Kaggle version)
- Link: kaggle.com/datasets/shayanfazeli/heartbeat
- Train: 87,554 heartbeats | Test: 21,892 heartbeats
- Classes: Normal, Supraventricular, Ventricular, Fusion, Other

## Requirements
- Python 3.x
- Google Colab (recommended)
- Libraries: pandas, numpy, matplotlib, scikit-learn, torch

## How to run
1. Open IA_Final_Project.ipynb in Google Colab
2. Enable GPU: Runtime → Change runtime type → GPU T4
3. Run all cells (Ctrl + F9)
4. The notebook auto-downloads the dataset — no manual upload needed
5. For the demo: upload any CSV file with 187 ECG values

## Results
| Model                 | Accuracy | F1 Macro | Loss   |
|-----------------------|----------|----------|--------|
| Logistic Regression   |  78.4%   |  58.0%   | 0.6713 |
| Random Forest         |  95.6%   |  83.4%   | 0.2431 |
| MLP                   |  93.3%   |  77.7%   | 0.2487 |
| Transformer (100 ep.) |  79.9%   |  58.8%   |  N/A   |

## Course
Artificial Intelligence — Yachay Tech — 2026
Instructor: Jonathan Cruz
