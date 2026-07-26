# Breast Cancer Detection using Machine Learning

A machine learning project for classifying breast tumors as benign or malignant, using both a classical CNN and a Hybrid Quantum-Classical CNN (QCNN) for comparison.

## 📌 Overview

This project applies machine learning techniques to the **Breast Cancer Wisconsin (Diagnostic) Dataset** to predict whether a tumor is benign or malignant. It compares the performance of a standard Convolutional Neural Network (CNN) against a Hybrid Quantum-Classical CNN (QCNN) approach.

## 🎯 Results

| Model | Accuracy |
|-------|----------|
| CNN   | See `ACCURACY OUTPUT CNN.jpeg` |
| QCNN (Hybrid Quantum-Classical) | **97%** |

The QCNN model outperformed the classical CNN baseline, demonstrating the potential of hybrid quantum-classical approaches for medical image/data classification tasks.

## 📂 Dataset

**Breast Cancer Wisconsin (Diagnostic) Dataset** from Kaggle:
🔗 https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

The dataset contains features computed from digitized images of fine needle aspirate (FNA) of breast masses, describing characteristics of the cell nuclei present.

## 🛠️ Technologies Used

- **Python**
- **Scikit-learn** – classical ML modeling and evaluation
- **Pandas** – data loading and preprocessing
- **Matplotlib** – visualization of results and accuracy plots

## 📁 Repository Structure

```
├── hybrid-qcnn-for-medical-diagnosis.ipynb   # Main notebook: data prep, model training, evaluation
├── ACCURACY OUTPUT CNN.jpeg                  # Accuracy plot for the classical CNN model
├── ACCURACY OUTPUT QCNN.jpeg                 # Accuracy plot for the hybrid QCNN model
└── README.md
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Saisruti-Mohanty/Breast-Cancer-Dectection.git
   cd Breast-Cancer-Dectection
   ```
2. Install dependencies:
   ```bash
   pip install scikit-learn pandas matplotlib numpy
   ```
3. Download the dataset from Kaggle (link above) and place it in the project directory.
4. Open and run `hybrid-qcnn-for-medical-diagnosis.ipynb` in Jupyter Notebook or Google Colab.

## 📊 Methodology

1. **Data Preprocessing** – Cleaning, normalization, and feature scaling of the diagnostic dataset.
2. **Model Building** – Training a classical CNN as a baseline model.
3. **Hybrid QCNN** – Building a hybrid quantum-classical CNN architecture for comparison.
4. **Evaluation** – Comparing accuracy and performance between both approaches.

## 📈 Future Work

- Expand hyperparameter tuning for both models
- Test on additional medical imaging datasets
- Explore other quantum ML architectures

## 👤 Author

**Saisruti Mohanty**
🔗 [GitHub](https://github.com/Saisruti-Mohanty) | [LinkedIn](https://www.linkedin.com/in/saisruti-mohanty-51956a327)

## 📄 License

This project is open source and available for educational and research purposes.
