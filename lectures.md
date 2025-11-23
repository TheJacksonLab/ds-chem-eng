---
layout: page
title: "Lecture Schedule"
permalink: /lectures/
---

# Tentative Lecture Schedule (Fall 2025)

This schedule is **tentative** and may be adjusted during the semester. Any updates will be
announced in class and on Canvas.

Abbreviations:
- **ISL** – *An Introduction to Statistical Learning with Python*  
- **PPNM** – *Python Programming and Numerical Methods*  
- **Prince** – *Understanding Deep Learning*  

Where notebook names are given (e.g. `CDS25_IntroPython.ipynb`), you can link to GitHub and
Google Colab once the notebooks are uploaded.

---

## Week-by-Week Plan

| Week | Date | Topic | Reading | Example Notebooks | Comments |
|------|------|-------|---------|-------------------|----------|
| 1 | Aug 26 | Course Overview and Software Ecosystem | ISL Ch. 1; Prince Ch. 1 | `CDS25_IntroPython.ipynb` |  |
| 1 | Aug 28 | Crash Course in Python | ISL Ch. 1; PPNM Ch. 1–5, 11, 12 (Python practice) | `CDS25_IntroPython.ipynb`; `CDS25_NumpyScipyMatrices.ipynb` | HW1 assigned |
| 2 | Sep 2 | Using Large Language Models for Science | Review of Python notebooks | `CDS25_IntroPython.ipynb`; `CDS25_NumpyScipyMatrices.ipynb` |  |
| 2 | Sep 4 | Exploratory Data Analysis *(Jingdan lecture)* |  | `CDS25_Pandas_EDA.ipynb` | HW1 due; HW2 assigned |
| 3 | Sep 9 | ML Method Overview and Linear Regression | ISL Ch. 3.1–3.3, 7.1; Prince Ch. 2 | `CDS25_LinearRegression_GradientDescent.ipynb` |  |
| 3 | Sep 11 | Regularization, Overfitting, and Partial Least Squares | ISL Ch. 6.1–6.4 | `CDS25_LassoRidgePLS.ipynb` | HW2 due; HW3 assigned |
| 4 | Sep 16 | Model Assessment: Cross-Validation | ISL Ch. 2.2, 5.1–5.3; Prince Ch. 5 | `CDS25_ModelAssessment.ipynb` | Projects introduced |
| 4 | Sep 18 | Molecular Featurization *(Zoom lecture)* |  | `CDS25_MolecularFeaturization.ipynb` | HW3 due; HW4 assigned |
| 5 | Sep 23 | Classification: Logistic Regression | ISL Ch. 4.1–4.3 | `CDS25_LogisticRegression.ipynb` |  |
| 5 | Sep 25 | Support Vector Machines | ISL Ch. 9.1–9.5 | `CDS25_SVM.ipynb` | HW4 due; HW5 assigned |
| 6 | Sep 30 | Decision Trees and Random Forests | ISL Ch. 8.1 | `CDS25_DecisionTrees.ipynb` |  |
| 6 | Oct 2 | Kernel Ridge Regression and Gaussian Process Regression | dmol.pub kernel chapter | `CDS25_GPRfromScratch.ipynb` | Project team selection due; HW5 due; HW6 assigned |
| 7 | Oct 7 | Data-Efficient Discovery with Active Learning |  | `CDS25_ActiveLearning_1D.ipynb` |  |
| 7 | Oct 9 | Data-Efficient Discovery with Bayesian Optimization |  | `CDS25_BayesianOptimization_1D.ipynb` | HW6 due |
| 8 | Oct 14 | **Exam 1** and Unsupervised Learning: Clustering *(Zoom lecture)* | ISL Ch. 12.1, 12.4; Prince Ch. 14 | `CDS25_KMeans.ipynb` | Exam 1 available online |
| 8 | Oct 16 | Unsupervised Learning: Dimensionality Reduction | ISL Ch. 12.3 | `CDS25_PCA_tSNE.ipynb` | Exam 1 due; HW7 assigned |
| 9 | Oct 21 | Explainable AI | dmol.pub XAI chapter | `CDS25_SHAP_ReactivityRatios.ipynb` |  |
| 9 | Oct 23 | Data Science in Industry: **Alix Schmidt (Dow)** | Guest lecture – Senior data scientist, Dow Chemical R&D Information Research Team |  | Project topic selection due; HW7 due; HW8 assigned |
| 10 | Oct 28 | Introduction to Deep Learning | ISL Ch. 10 |  |  |
| 10 | Oct 30 | Neural Networks I | ISL Ch. 10; Prince Ch. 3, 4, 5 | `CDS25_NeuralNetworkWithKeras_DeepDive.ipynb` | HW8 due; HW9 assigned |
| 11 | Nov 4 | Neural Networks II | ISL Ch. 10; Prince Ch. 6, 7 | `CDS25_Keras_NNRegression.ipynb` |  |
| 11 | Nov 6 | Neural Networks III | ISL Ch. 10; Prince Ch. 8, 9 | `CDS25_Keras_NNClassification.ipynb` | HW9 due; HW10 assigned |
| 12 | Nov 11 | Convolutional Neural Networks | ISL Ch. 10; Prince Ch. 10 | `CDS25_Keras_ConvNet_Example.ipynb` |  |
| 12 | Nov 13 | Graph Neural Networks | Prince Ch. 13; Distill GNN intro and understanding GNNs articles | `CDS25_DeepChem_GraphConv.ipynb` | HW10 due |
| 13 | Nov 18 | **Exam 2** and Neural Networks for Time Series and Language | ISL Ch. 11 | `CDS25_RNN_weatherforecasting.ipynb` | Exam 2 available online |
| 13 | Nov 20 | Attention and Transformers | Prince Ch. 12 |  | Exam 2 due |
| 13 | Nov 25 | **Fall Break – No Class** |  |  |  |
| 13 | Nov 27 | **Fall Break – No Class** |  |  |  |
| 14 | Dec 2 | Deep Learning and Ethics *(Zoom lecture)* | Prince Ch. 20 |  |  |
| 14 | Dec 4 | Final Project Presentations I |  |  | Project reports due |
| 15 | Dec 9 | Final Project Presentations II |  |  |  |

*Instructor note: In previous offerings, the semester ended with one extra neural-network lecture
slot; a future revision of the course may replace one of the neural-network lectures with a new topic.*

---

## Slides and Colab Links

Once lecture materials are uploaded, you can add them here, for example:

```markdown
- Week 1, Aug 26 – Course Overview  
  - [Slides (PDF)]({{ '/assets/slides/01_intro.pdf' | relative_url }})  
  - [Intro Python Notebook (Colab)](https://colab.research.google.com/github/TheJacksonLab/ds-chem-eng/blob/main/notebooks/CDS25_IntroPython.ipynb)
```

Use the `assets/` and `notebooks/` folders in this repository to organize lecture materials.

