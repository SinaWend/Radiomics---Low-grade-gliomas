
# Radiomics and Machine Learning for Low-Grade Gliomas

## What Is The Project About?

The project tackles the use of radiomics and machine learning to help predict the 1p/19q codeletion status in Low-Grade Gliomas (LGGs). This is an important genetic marker that helps doctors decide on the best treatment plans. Our goal is to make this prediction using non-invasive methods, specifically by analyzing MRI scans with machine learning.

---

## Overview

1. **MRI Data**: We start with pre-operative MRI scans of LGG patients, focusing on areas of interest.
2. **Feature Extraction**: Using a Python library called Pyradiomics, we extract 640 features from the MRI images. These include tumor shapes, textures, and intensity patterns.
3. **Feature Selection**: Feature selection algorithms (like Recursive Feature Elimination and Lasso Regression) are used to pick the most important ones.
4. **Machine Learning Magic**: We train different models—like Random Forests, SVMs, and Logistic Regression—to classify the tumors based on their genetic status.
5. **Performance Check**: We measure how well our models work using metrics like accuracy, precision, recall, and F1 scores. 
---

## Highlights

- **Dataset**: MRI scans from 105 patients, split into two groups based on 1p/19q deletion status.
- **Best Models**: Logistic Regression and Linear Discriminant Analysis stood out with high accuracy and F1 scores.
- **Challenges**: Small dataset size and class imbalance.
- **Future Ideas**: Bigger datasets, more advanced computer vision models and analysis of the explainability.


---

## Contributors

- **Ramona Koch**  
- **Sina Wendrich**  
**Tutor**: Sofia Monteiro  
Course: Machine Learning in Bioengineering – Instituto Superior Técnico

---

