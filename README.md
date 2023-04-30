# Exploring Dynamic Mode Decomposition

## Abstract

With the rise of big data, it is important from a computational standpoint to effectively extract low-rank information from high dimensional structures like data matrices. To relieve this challenge, several dimensionaly reduction techniques have been pioneered like Singular Value Decomposition (SVD), Principal Component Analysis (PCA), and Dynamic Mode Decomposition (DMD). This project primarily explores DMD, which reduces data into its spatial modes and associated temporal dynamics. To illustrate its capabilities, it is applied to Electrocorticography (ECG) recordings in the domain of neuroscience. Variations of DMD, like Bagging, Optimized DMD (BOPDMD) are briefly explored as well.

## Introduction

### Motivation

As a Physics & Data Science major, I've garnered a strong interest in the intersections of both worlds. After having been introduced to Linear Algebra and Machine Learning, as well as methods that incorporate them together like PCA, I wanted to explore time-series analysis. A suggesion by Professor Santillana on DMD resulted in this project.

### Problem Statement

Being able to model complex physical systems can provide insight into the underlying physics and governing equations. The problem addressed in this project report is the application of Dynamic Mode Decomposition (DMD) to Electrocorticography (ECG) recordings in neuroscience for data diagnosis and forecasting. DMD is a data analysis method used to extract relevant patterns and modes from high-dimensional, time-varying data sets. ECG recordings are a type of neuroimaging data that provide high temporal resolution and high spatial specificity of brain activity. However, they present challenges for data analysis due to their large size, high dimensionality, and noisy nature. The goal of this project is to explore the use of DMD as a method for diagnosing and forecasting ECoG data by identifying relevant patterns and modes that capture the underlying dynamics of brain activity. By demonstrating the effectiveness of DMD for ECG data analysis, this project aims to show the possibilities with DMD.

## References

\[1\] Kutz, N. J., Brunton, S. L., Brunton, B. W., &amp; Proctor, J. L. (2017). Dynamic mode decomposition: Data-driven modeling of Complex Systems. Society for Industrial &amp; Applied Mathematics.

\[2\] Sashidhar, D., & Kutz, J. N. (2021). Bagging, optimized dynamic mode decomposition (BOP-DMD) for robust, stable forecasting with spatial and temporal uncertainty-quantification. ArXiv. https://doi.org/10.1098/rsta.2021.0199

I used PyDMD extensively in the project as well as their useful tutorials:
https://github.com/mathLab/PyDMD
