# Parkinson’s Disease Voice Classification

This project focuses on detecting Parkinson’s disease (PD) using voice recordings and acoustic features. By analyzing speech signals, the goal is to distinguish between healthy individuals and those with PD based on subtle changes in tone and vocal patterns.

---

## 📂 Dataset

- Total subjects: 31

- Individuals with Parkinson’s disease (PD): 23

- Healthy individuals: 8

- Data type: Recorded voice samples and extracted acoustic features

- Target: Binary classification – Healthy vs. PD

---

# 🎯 Project Objective

The aim of this project is to build a machine learning model that:

- Predicts whether an individual has Parkinson’s disease.

- Accurately separates healthy subjects from those with PD using their voice features.


---

## 🛠️ Methods & Tools

- Language: Python

- Notebook: [parkings.ipynb](parkings.ipynb)

---

## Core Libraries:

- numpy, pandas – data preprocessing and manipulation

- matplotlib, seaborn – exploratory data analysis and visualization

- scikit-learn – machine learning modeling and evaluation


---

## 📊 Approach

- Exploratory Analysis

- Feature scaling and splitting into training/testing sets

- Model Training

- A Random Forest Classifier was applied to classify patients as Healthy or PD.

---

## 🚀 Results

- Model Used: Random Forest Classifier

- Accuracy Achieved: 100% (1.0)

- The model was able to perfectly distinguish between healthy individuals and those with Parkinson’s disease in this dataset.

---

## 📦 Project Structure
```plaintext
├── README.md              # Project documentation
├── parkings.ipynb         # Main Jupyter Notebook 
```

---

## 🔧 Installation & Usage

Clone this repository and navigate into the project folder:

## Clone the repository
```bash
git clone https://github.com/JOEL-TAMAKLOE/parkinsons-disease.git
cd parkinsons-disease
```

## 📌 Future Work

- Explore additional models such as SVM or Gradient Boosting for benchmarking.

- Apply more approaches and feature engineering with advanced signal processing methods (e.g., MFCC, spectral entropy).

- Experiment with deep learning architectures for raw audio analysis.

- Develop a simple web-based demo application for healthcare use cases.

## 🤝 Contribution

Contributions, suggestions, and improvements are welcome!
Feel free to fork this repository and submit pull requests.

## 📜 License

This project is licensed under the MIT License.
