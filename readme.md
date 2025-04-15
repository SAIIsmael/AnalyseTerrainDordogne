# Land Cover Classification in Dordogne Using Deep Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-CNN%2C%20MLP%2C%20RNN-red.svg)
![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

## Overview

This project focuses on **land cover classification** using **multi-temporal Sentinel-2 satellite imagery** over a region in Dordogne, France.  
The goal was to build and evaluate multiple deep learning models to classify satellite pixels into five land-use classes based on eight optical image captures.

> Built entirely in **Python**, using libraries like TensorFlow, Keras, NumPy, and Matplotlib.

---

## Features

- Real-world Sentinel-2 time-series satellite data
- Classification into 5 distinct land cover types
- Implemented and compared several neural network architectures:
  - MLP (Multi-Layer Perceptron)
  - 1D CNN
  - 2D CNN
  - 2D CNN with Mish activation
  - 3D CNN
  - RNN (Recurrent Neural Network)
  - Hybrid MLP + CNN2D

---

## Best Model

The **2D CNN with Mish activation** function achieved the best classification performance.

---

## Project Structure

```bash
├── CNN1D_rendu.ipynb           # Final 1D CNN notebook
├── CNN2D_avec_mish_80E.ipynb   # Best model implementation
├── CNN3D.ipynb                 # 3D CNN experiments
├── MLP.ipynb                   # Basic MLP model
├── RNN.ipynb                   # RNN classification attempt
├── soumissions/                # Submission CSV files
└── readme.md                   # Original README
```

---

## Getting Started

**Requirements**

- Python 3.8+
- Jupyter Notebook
- TensorFlow
- NumPy
- Pandas
- Matplotlib

---

## Installation 
```bash
pip install tensorflow numpy pandas matplotlib
```

---

## Usage
```bash
jupyter notebook CNN2D_avec_mish_80E.ipynb
```

---

## Authors

- [CHERFAOUI Youcef (21509641)](https://gitlab.com/Evlose) - <youcef.cherfaoui@etu.umontpellier.fr>
- [MOREL Anthony (21601860)](https://gitlab.com/zero.un) - <anthony.morel@etu.umontpellier.fr>
- [LAROUG Nahla (21715023)](https://gitlab.com/nlaroug) - <nahla.laroug@etu.umontpellier.fr>
- [SAÏ Ismaël (20135723)](https://github.com/SAIIsmael) - <sai.ismael@outlook.com>

---

## License 

This project is licensed under the MIT License. You are free to use, modify, and share it.

