# Deep Learning 

A collection of methods of deep learning covering classical and modern methods, implemented using Keras, TensorFlow, and PyTorch.

---

## Notebooks

### 1. Logistic Regression
**File:** `Logistic_Regression.ipynb`

Implemented logistic regression and regularized logistic regression from scratch using three optimization strategies:
- Batch Gradient Descent
- Stochastic Gradient Descent
- Mini-Batch Gradient Descent

**Dataset:** Wisconsin Diagnostic Breast Cancer (WDBC) — binary classification (malignant vs. benign)  
**Key concepts:** Feature scaling, objective value plots, training vs. testing accuracy comparison

---

### 2. CNN for Image Classification
**File:** `CNN_CIFAR10.ipynb`

Built a Convolutional Neural Network to classify images from the CIFAR-10 dataset.

**Dataset:** CIFAR-10 (10 classes, 60K images)  
**Key concepts:** Batch Normalization, Dropout regularization, training/validation accuracy curves, hyperparameter tuning

---

### 3. Seq2Seq Bidirectional LSTM — Machine Translation
**File:** `Seq2Seq_BiLSTM_Translation.ipynb`

Extended a standard LSTM encoder-decoder model to use a Bidirectional LSTM encoder for English-to-Dutch neural machine translation.

**Dataset:** Anki parallel corpus (manythings.org)  
**Key concepts:** Sequence-to-sequence architecture, Bi-LSTM encoder, unidirectional LSTM decoder, state concatenation

---

### 4. Supervised Autoencoder
**File:** `Supervised_Autoencoder_MNIST.ipynb`

Built and compared a standard autoencoder vs. a supervised autoencoder to learn discriminative low-dimensional features for classification.

**Dataset:** MNIST (handwritten digits, 60K training samples)  
**Key concepts:** Dimensionality reduction, reconstruction loss, classification head, feature visualization

---

## Setup

```bash
pip install tensorflow keras torch numpy scikit-learn matplotlib
```

> Some notebooks were trained on Google Colab for GPU acceleration. It is recommended to run them there for faster training.

---

## Author

**Palak Sood**  

