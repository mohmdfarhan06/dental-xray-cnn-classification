# Dental X-Ray Image Classification using CNN

## Overview
A deep learning application that classifies dental X-ray images into four categories:
- Cavity
- Filling
- Implant
- Impacted Tooth

## Project Structure
```text
dental-xray-cnn-classification/
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
├── pytest.ini
├── Dockerfile
├── .github/
│   └── workflows/
│       └── ci.yml
├── data/
│   ├── README.md
│   ├── raw/
│   ├── processed/
│   └── sample/
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_cnn_training.ipynb
│   └── 04_model_evaluation.ipynb
├── src/
│   ├── config.py
│   ├── data/
│   ├── models/
│   ├── training/
│   └── evaluation/
├── models/
├── app/
│   ├── app.py
│   └── utils.py
├── tests/
├── reports/
└── screenshots/
```

## How to Run Tests
```bash
pytest
```
