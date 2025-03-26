# Cybersecurity-Threat-Classification

## Overview
This project classifies cybersecurity threats using machine learning models, including Random Forest, SVM, and MLP Classifier. The dataset undergoes preprocessing before training and evaluation.

## Dataset
CICIDS2017 dataset (available at https://www.unb.ca/cic/datasets/ids.html)

## Requirements
Ensure you have the following installed:
- Python 3.11
- Required Python libraries (install using `pip install -r requirements.txt`)

## Installation
1. Clone the repository:
   ```bash
   git clone <https://github.com/srishti-chordia/Cybersecurity-Threat-Classification>
   cd <Cybersecurity Threat Classification>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Code
1. **Preprocess the Data**
   ```bash
   python preprocess.py
   ```
2. **Train and Evaluate Models**
   ```bash
   python train_models.py
   ```
3. **Run Neural Network Model (MLP Classifier)**
   ```bash
   python mlp_classifier.py
   ```
4. **Generate Performance Comparison Graphs**
   ```bash
   python visualize_results.py
   ```

## Outputs
- Model evaluation metrics (accuracy, precision, recall, F1-score)
- Performance comparison graphs

## Notes
- Ensure the dataset file is in the correct directory before running the scripts.
- Modify `config.py` if you need to adjust parameters.

For any issues, feel free to raise an issue in the repository.

