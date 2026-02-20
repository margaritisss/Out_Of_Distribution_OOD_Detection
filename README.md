# Out-of-Distribution Detection and Neural Collapse Analysis

**Authors:** Georgios Margaritis and Liam Loughman

## Overview
This project explores Out-of-Distribution (OOD) detection methods using a ResNet-18 model trained on CIFAR-100 (In-Distribution) and tested against CIFAR-10 (Out-of-Distribution). 

It implements and compares several OOD scoring methods:
1. Maximum Softmax Probability (MSP)
2. MaxLogit
3. Energy Score
4. Mahalanobis Distance
5. ViM (Virtual-logit Matching)
6. NECO (Neural Collapse based OOD)

Additionally, the notebook analyzes the Neural Collapse phenomenon during the terminal phase of training.

## Environment Setup
To run this notebook, you will need a Python environment with Jupyter Notebook and the required deep learning and data science libraries installed.

1. **Clone or download** the repository containing the `new_2.ipynb` file.
2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv ood_env
   source ood_env/bin/activate  # On Windows use: ood_env\Scripts\activate
   pip install requirements.txt
3. **Download the weights of the model** from the [link](https://drive.google.com/file/d/1ksITLO8oXzHGmPJ84isre7nyH1AAwalq/view?usp=drive_link) if you don't want to train the model from scratch.

## The Report 
Please find our report in the [link](https://drive.google.com/file/d/1lqgxPBOZ1iN8fc27WwnA5lm2P2OWC6Tr/view?usp=sharing)
