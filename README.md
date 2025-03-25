# Cybersecurity Threat Classification

## Overview
This project applies machine learning techniques to classify cybersecurity threats using the CICIDS2017 dataset. The models used include Random Forest and Support Vector Machine (SVM) to distinguish between benign and DDoS attack traffic.

## Prerequisites
Ensure you have the following installed before running the code:
- Python 3.x
- Jupyter Notebook or Google Colab (optional)
- Required Python libraries:
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn
  ```

## How to Run the Code

1. **Download the Dataset**
   - Ensure that `Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv` is in the working directory.

2. **Run the Python Script**
   - If using a Jupyter Notebook or Google Colab, execute each cell sequentially.
   - If using a standalone Python script, run:
     ```bash
     python script_name.py
     ```

3. **Code Workflow**
   - **Load Dataset**: Reads the dataset into a Pandas DataFrame.
   - **Data Exploration**: Displays basic statistics and visualizations.
   - **Data Cleaning**: Handles missing values and duplicate records.
   - **Feature Engineering**: Performs feature selection and transformation.
   - **Model Training**: Trains Random Forest and SVM classifiers.
   - **Model Evaluation**: Computes accuracy, precision, recall, and F1-score.

4. **Interpreting the Output**
   - The script will print model performance metrics and display visualizations.
   - Confusion matrices and feature importance graphs will help in understanding classification effectiveness.

## Notes
- Modify hyperparameters in the script for better tuning.
- Additional datasets can be integrated by following the preprocessing steps.

## Contact
For any issues or inquiries, feel free to reach out.
