<h2> Hi, I'm Sumon Maiti! <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50"></h2>
<img align='right' src="https://media.giphy.com/media/ieyl9zmCjO4b4t6qoY/giphy.gif" width="230">
<p><em>Student at <a href="https://aot.edu.in/">Academy of Technology</a><img src="https://media.giphy.com/media/fYSnHlufseco8Fh93Z/giphy.gif" width="30">
</em></p>

[![Twitter: Sumon Maiti](https://img.shields.io/twitter/follow/SumonMaiti?style=social)](https://x.com/Sumon_Maiti)
[![Linkedin: Sumon Maiti](https://img.shields.io/badge/-SumonMaiti-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/thaianebraga/)](https://www.linkedin.com/in/sumon-maiti/)
[![GitHub Sumon Maiti](https://img.shields.io/github/followers/SumonMaiti?label=follow&style=social)](https://github.com/SumonMaiti)


### <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50">



# Prediction and Optimization of Antenna Parameters Using Machine Learning
Checkout in google colab -> 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GgqcEN1qy-S-UhRnD5KhCyJeChZ6wtCr?usp=drive_open&authuser=2#scrollTo=0Zco9oB2OvMH)
## Overview

This repository presents a machine learning-based framework for the prediction and optimization of circular microstrip patch antenna parameters. The project combines CST Studio Suite simulations with modern machine learning techniques to accelerate the antenna design process and reduce the dependence on repetitive electromagnetic simulations.

A circular microstrip patch antenna for Sub-6 GHz wireless applications was designed and analyzed through parametric studies. Key antenna parameters were varied to generate a simulation dataset, which was subsequently used to train multiple machine learning regression models for bandwidth and gain prediction.

The optimized antenna parameters were obtained using Differential Evolution optimization and validated through CST simulations.

---

## Project Objectives

- Design a circular microstrip patch antenna for Sub-6 GHz applications.
- Perform parametric analysis to study the effect of antenna dimensions.
- Generate a simulation dataset using CST Studio Suite.
- Develop machine learning models for antenna performance prediction.
- Compare the performance of different regression algorithms.
- Optimize antenna parameters using Differential Evolution.
- Validate machine learning predictions using CST simulations.

---

## Antenna Performance

| Parameter | Value |
|------------|------------|
| Bandwidth | 3.2 GHz – 10.14 GHz |
| Bandwidth Span | 6.94 GHz |
| Return Loss (S11) | -45.5 dB |
| VSWR | 1.01 |
| Gain | 1.19 dBi |

---

## Machine Learning Models Used

The following regression models were implemented and evaluated:

- Linear Regression
- Random Forest Regression
- Support Vector Regression (SVR)
- Extra Trees Regressor

### Best Performing Models

- **Bandwidth Prediction:** Support Vector Regression (SVR)
- **Gain Prediction:** Extra Trees Regressor

---

## Evaluation Metrics

Model performance was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Coefficient of Determination (R² Score)

---

## Optimization Technique

Differential Evolution (DE) was used to determine the optimal antenna parameters under bandwidth constraints.

### Optimized Parameters

| Parameter | Value |
|------------|------------|
| Xrad | 7.4 mm |
| Yrad | 7.0 mm |
| Ycenter | 12.7 mm |

---

## Project Workflow

```text
Antenna Design in CST
          ↓
Parametric Analysis
          ↓
Dataset Generation
          ↓
Data Preprocessing
          ↓
Machine Learning Training
          ↓
Model Evaluation
          ↓
Differential Evolution Optimization
          ↓
Prediction of Optimal Parameters
          ↓
CST Verification
```

---

## Repository Structure

```text
├── Antenna_ML_Optimization.ipynb
├── README.md
├── Dataset/
│   └── antenna_dataset.csv
├── Results/
│   ├── S11_Plots
│   ├── Gain_Plots
│   ├── Correlation_Heatmap
│   ├── Feature_Importance
│   └── Actual_vs_Predicted
└── Figures/
```

---

## Technologies Used

- Python
- CST Studio Suite
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Predict-and-Optimize-Antenna-Parameter-using-ML.git
```

Install required packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy
```

---

## Results

The integration of machine learning with CST simulations significantly reduced the need for repetitive simulations while maintaining accurate prediction of antenna characteristics.

Key outcomes include:

- Wideband antenna operation from 3.2 GHz to 10.14 GHz.
- Accurate bandwidth and gain prediction using machine learning.
- Successful optimization using Differential Evolution.
- CST validation of machine learning optimized parameters.
- Reduced design time and computational effort.

---

## Future Scope

- Generate larger datasets for improved model accuracy.
- Explore deep learning architectures for antenna prediction.
- Include additional antenna parameters such as radiation efficiency and resonant frequency.
- Fabricate and experimentally validate the antenna using a Vector Network Analyzer (VNA).
- Develop fully automated AI-assisted antenna design frameworks.

---
## Team

This project was developed as part of the B.Tech Final Year Project by:

- Sumon Maiti
- Rajat Chakraborty
- Sayan Pal
- Sumit Kumar Bhakat
- Subhadep Dey

### Mentor

Special thanks to **Prof. Rakhi Neogi** for her invaluable guidance, support, and mentorship throughout the project.

⭐ We are grateful for her encouragement and technical insights, which helped shape this work from concept to completion.
## Authors

**Sumon Maiti**  
Bachelor of Technology (Electronics and Communication Engineering)

Academy of Technology, West Bengal, India

---

## License

This project is intended for academic and research purposes.
