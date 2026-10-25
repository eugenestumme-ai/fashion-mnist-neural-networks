# Fashion-MNIST Neural Networks & Feature Analysis

Hands-on comparison of hand-crafted feature extraction versus raw-pixel machine learning models, paired with neural network depth evaluations and hidden layer weight visualizations for AIM 350 coursework.

## 🚀 Project Overview
This project examines image classification workflows using the Fashion-MNIST dataset. It transitions from rule-based feature engineering to fully automated deep representations using multi-layer perceptrons (MLPs) and explores internal model interpretability.

## 🔑 Key Components & Technical Highlights
* **Hand-Crafted vs. Raw Pixels:** Engineered domain-specific features (upper-row brightness, center vertical stripe, and overall intensity) and trained a Logistic Regression classifier, comparing its performance and feature weights against a raw-pixel model (784 dimensions).
* **Error Diagnosis:** Analyzed classification failure cases to identify limitations of average-based image rules and discussed the trade-offs of interpretability versus black-box flexibility.
* **Network Depth Evaluation:** Benchmarked model performance, overfitting behavior, and training times across 0 hidden layers (LogReg), 1 hidden layer (64 units), and 3 hidden layers (128-64-32) across all 10 categories.
* **Hidden Layer Visualization:** Plotted learned weights of the first hidden layer (using seismic colormaps) to interpret learned edge, orientation, and texture filters, and authored an executive memo evaluating architectural selection for business operations.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** TensorFlow / Keras, Scikit-Learn, NumPy, Matplotlib, Pandas
* **Environment:** Google Colab / Jupyter Notebooks

---
*Created by Eugene Stumme | [GitHub Profile](https://github.com/eugenestumme-ai)*
