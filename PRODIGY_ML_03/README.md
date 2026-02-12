# 🐱🐶 Cats vs Dogs Image Classification using SVM

## 📌 Project Overview

This project implements a **Support Vector Machine (SVM)** to classify images of **cats and dogs** using the **Kaggle Dogs vs Cats dataset**.
It demonstrates a **classical machine learning approach** (not deep learning) by converting images into numerical feature vectors and training an SVM classifier.

---

## 📂 Dataset

**Source:** Kaggle
🔗 [https://www.kaggle.com/c/dogs-vs-cats/data](https://www.kaggle.com/c/dogs-vs-cats/data)

The dataset contains labeled images of cats and dogs.

### Folder Structure

```
dataset/
 └── train/
      ├── cat.0.jpg
      ├── dog.0.jpg
      ├── cat.1.jpg
      ├── dog.1.jpg
      └── ...
```

---

## ⚙️ Requirements

Install the required Python libraries:

```bash
pip install numpy opencv-python scikit-learn
```

### Libraries Used

* Python 3.x
* NumPy
* OpenCV
* Scikit-learn

---

## 🧠 Methodology

1. Load images from the dataset
2. Resize images to **64 × 64**
3. Convert images into **flattened feature vectors**
4. Assign labels:

   * Cat → `0`
   * Dog → `1`
5. Split data into training and testing sets
6. Train an **SVM classifier with RBF kernel**
7. Evaluate model performance

---

## 🧪 Model Used

* **Algorithm:** Support Vector Machine (SVM)
* **Kernel:** RBF (Radial Basis Function)
* **Hyperparameters:**

  * `C = 1`
  * `gamma = scale`

---

## 📊 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score

### Sample Output

```
Accuracy: ~78%

Precision, Recall, and F1-score are balanced for both classes.
```

> Note: Accuracy may vary depending on dataset size and system performance.

---

## ▶️ How to Run

1. Download and extract the dataset
2. Place images in `dataset/train/`
3. Run the Python script or Jupyter Notebook:

   ```bash
   python svm_cats_dogs.py
   ```

   or open the `.ipynb` file and run all cells

---

## 📌 Key Points

* SVM requires **numerical feature vectors**, not raw images
* Suitable for **small to medium-sized datasets**
* Faster than deep learning models on limited hardware
* CNNs are preferred for large-scale image classification

---

## 🚀 Future Improvements

* Use **HOG (Histogram of Oriented Gradients)** features
* Apply **PCA** for dimensionality reduction
* Perform **hyperparameter tuning**
* Compare performance with CNN models

---

## 📄 Conclusion

This project demonstrates how classical machine learning techniques like SVM can be effectively applied to image classification problems by proper preprocessing and feature extraction.

---
