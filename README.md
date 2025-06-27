# 🚢 Titanic Survival Prediction with Deep Learning


This project demonstrates how to build, train, and evaluate a simple neural network using TensorFlow/Keras to predict Titanic passenger survival. Built with clarity and ease-of-understanding in mind, this walkthrough reflects the tutorial by James Leslie on Kaggle.

---

## 🧠 Project Highlights

- One-hot encoding of categorical features (`Sex`, `Embarked`, `Title`)
- Pre-processing
- Neural Network architecture with:
  - Input layer based on training features
  - Dense hidden layers with ReLU activation
  - Dropout for regularization
  - Sigmoid output for binary classification
- Training with Adam optimizer and Binary Crossentropy loss
- Evaluation using 5-fold Stratified Cross-Validation
---

## 📊 Model Performance

| Metric             | Score     |
|--------------------|-----------|
| Validation Accuracy| ~86.33%   |
| Loss Function      | Binary Crossentropy |
| Optimizer          | Adam      |
| Cross-Validation   | StratifiedKFold (n=5) |

---

### 📌 Requirements
  Python 3.10 or 3.11

  TensorFlow

  scikit-learn

  pandas, numpy, matplotlib

  scikeras (for KerasClassifier wrapper)

### 🧾 Output Table
    Here’s a sample of the model’s prediction on test data:

     PassengerId  	Prediction (Survived)
      892          	0
      893	          1
      894	          0
      895	          0
      896	          1
      ...	          ...

## Happy Learning
