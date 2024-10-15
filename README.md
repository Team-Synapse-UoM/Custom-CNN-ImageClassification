# Custom-CNN-ImageClassification
CNN for image classification

Dataset - [MNIST](https://archive.ics.uci.edu/dataset/683/mnist+database+of+handwritten+digits)

## Overview

<p>
  <em>Developed with the software and tools below.</em>
</p>
<p>
<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=python&logoColor=yellow" alt="Python">
<img src="https://img.shields.io/badge/Conda-44A833.svg?style=flat&logo=anaconda&logoColor=white" alt="Anaconda">
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style=flat&logo=jupyter&logoColor=white" alt="Jupyter">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C.svg?style=flat&logo=pytorch&logoColor=white" alt="PyTorch">
<img src="https://img.shields.io/badge/NumPy-013243.svg?style=flat&logo=numpy&logoColor=white" alt="NumPy">
<img src="https://img.shields.io/badge/Pandas-150458.svg?style=flat&logo=pandas&logoColor=white" alt="Pandas">
<img src="https://img.shields.io/badge/Matplotlib-447699.svg?style=flat&logo=matplotlib&logoColor=white" alt="Matplotlib">
</p>




## Project Lifecycle

Separate sections tested out in jupyter notebooks. Final scripts and project deployment available in [src](src).

1. Problem Identification
2. Collecting Data
3. Pre-Processing Data
4. Analyzing Data
5. Data Handling
6. Model Evaluation/Monitoring
7. Model Training

## Project Structure

```
|—— data
|    |—— test.csv
|—— feature_engineering.ipynb
|—— main.ipynb
|—— model.pkl
|—— model_building.ipynb
|—— src
|    |—— Dockerfile
|    |—— Overview.md
|    |—— data
|        |—— clean.csv
|        |—— smartwatches.csv
|        |—— test.json
|    |—— dummys
|        |—— Brand
|        |—— Dial Shape
|        |—— Model Name
|        |—— Strap Material
|        |—— numerical_col
|    |—— models
|        |—— model.pkl
|    |—— main.py
|    |—— config.py
|    |—— data.py
|    |—— predict.py
|    |—— requirements.txt
|    |—— test.py
|    |—— train.py
|    |—— test.json
```