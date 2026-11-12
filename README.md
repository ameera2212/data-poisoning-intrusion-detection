# Data Poisoning in Intrusion Detection Systems

## Project Overview
This project investigates the effects of label-flipping data poisoning attacks on machine learning-based Intrusion Detection Systems (IDS).

We will train a machine learning model using a public cybersecurity dataset containing normal and malicious network traffic. We will then simulate label-flipping attacks at different poisoning levels and evaluate a simple defence method.

## Project Objectives
- Develop a baseline machine learning-based intrusion detection model.
- Simulate label-flipping attacks at 5%, 10%, and 20%.
- Evaluate the impact of poisoning on intrusion detection performance.
- Investigate a simple defence method.
- Compare accuracy, precision, recall, F1-score, and false positive rate.

## Tools
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Google Colab
- GitHub

## Team Members
- Ameera Ali
- Joure Alteneiji
- Maryan Ashkanani

## Project Status
Deliverable 1: Research and project planning.

Dataset selection, model implementation, poisoning experiments, and defence evaluation are planned for the next stages.

## How to Run the Project

1. Download the CIC-IDS2017 dataset from:
   https://www.kaggle.com/datasets/dhoogla/cicids2017

2. Open Google Colab:
   https://colab.research.google.com/

3. Open `code/Data_Poisoning_IDS.ipynb`.

4. Upload the eight CIC-IDS2017 Parquet files
   into the Colab `/content` directory.

5. Run all notebook cells in order.

6. View the experimental results in the notebook.
   Generated CSV and graphs are saved in `/content/results`.

## Requirements

- Python 3
- pandas
- numpy
- scikit-learn
- matplotlib
- pyarrow

## Experiments

The project compares:
- Original Random Forest intrusion detection model
- 5%, 10%, and 20% label-flipping attacks
- Cross-validated label-consistency defence

All models are evaluated using the same clean test set.

