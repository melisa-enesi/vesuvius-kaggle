# Vesuvius Challenge – Surface Detection (Kaggle)

## Project Overview
This project explores the **Vesuvius Challenge**, a Kaggle competition focused on detecting hidden ink in high-resolution CT scans of ancient scroll fragments that were carbonized during the eruption of Mount Vesuvius in 79 AD.

The goal of the challenge is to use computer vision techniques to identify where ink is present without physically opening the fragile scrolls.

---

## Problem Type
**Computer Vision • Image Processing • Binary Classification / Segmentation**

We aim to predict the probability that a scroll fragment contains ink based on grayscale CT scan imagery.

---

## Dataset
The dataset contains ~27GB of high-resolution scan data including:

- `train_images/` – CT scan slices of scroll fragments  
- `train_labels/` – Ground truth masks indicating ink locations  
- `test_images/` – Unlabeled scan slices used for submission  
- `train.csv / test.csv` – Fragment metadata  

Because the dataset is extremely large, it is **not included in this repository** and is ignored via `.gitignore`.

---

## Pipeline Built
This repository demonstrates an **end-to-end machine learning workflow**:

1. Environment setup and dependency installation  
2. Large dataset handling and directory management  
3. Image loading and preprocessing using OpenCV  
4. Dataset exploration and visualization  
5. Baseline feature engineering  
6. Baseline prediction generation  
7. Kaggle submission file creation  
8. Reproducible workflow using Git & GitHub  

The final pipeline generates a valid `submission.csv` file for the competition.

---

## Tech Stack
- Python  
- NumPy  
- Pandas  
- OpenCV  
- Matplotlib  
- scikit-learn  
- Jupyter Notebook  

---

## Key Takeaways
This project demonstrates the ability to:

- Work with very large real-world datasets  
- Build a reproducible ML pipeline from scratch  
- Apply computer vision preprocessing techniques  
- Generate competition-ready prediction outputs  

---

## Repository Contents
```
vesuvius.ipynb     → main notebook with full pipeline
submission.csv     → example generated submission file
.gitignore         → excludes large dataset files
```

---

## Author
Data Science student exploring computer vision and Kaggle competitions.
