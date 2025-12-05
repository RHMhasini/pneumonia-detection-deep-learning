# Pneumonia Detection from Chest X-rays

## Project Overview
Deep learning project for detecting pneumonia from chest X-ray images using CNN and transfer learning.

## Current Progress
- Dataset organized (5,856 images)
- Simple CNN baseline trained (76.44% test accuracy)
- Full evaluation and visualization completed
- ResNet18 transfer learning (in progress)

## Dataset
- **Source:** Kaggle Chest X-Ray Images (Pneumonia)
- https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
- **Train:** 4,310 images
- **Validation:** 922 images
- **Test:** 624 images
- **Classes:** NORMAL (26%), PNEUMONIA (74%)

## Models

### Simple CNN (Baseline)
- **Architecture:** 4 Conv blocks + 2 FC layers
- **Parameters:** 26M
- **Test Accuracy:** 76.44%
- **Sensitivity:** 99.49% (excellent at detecting pneumonia)
- **Specificity:** 38.03% (room for improvement)
- **AUC-ROC:** 0.9168

## Tech Stack
- **Framework:** PyTorch
- **Platform:** Google Colab (Tesla T4 GPU)
- **Libraries:** torchvision, scikit-learn, pandas, matplotlib

## Files
- `models/` - Trained model weights
- `results/` - Training history, metrics, visualizations
- `notebooks/` - Jupyter notebooks


## Author
Hasini Herath

