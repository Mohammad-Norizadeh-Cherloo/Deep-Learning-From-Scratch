# Deep Learning From Scratch

**Complete from-scratch implementations of core Deep Learning models with full manual forward & backward passes**

![Deep Learning From Scratch](images/Deep-Learning-From-scratch.png)

**Author:** Mohammad Norizadeh Cherloo  
Educator & Researcher in Machine Learning, Deep Learning, Neural Decoding, Biomedical Signal Processing, and Brain-Computer Interfaces

[![Website](https://img.shields.io/badge/Website-onlinebme.com-blue)](https://onlinebme.com/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-green)](https://scholar.google.com/citations?user=fIKpYm8AAAAJ)
[![YouTube](https://img.shields.io/badge/YouTube-@Mrcherloo-red)](https://www.youtube.com/@Mrcherloo)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/mohammad-norizadeh-cherloo/)

---

### About This Repository

This repository contains **from-scratch implementations** of fundamental Deep Learning algorithms.  

Unlike most repositories that only call high-level libraries, here the core components (forward pass, backward pass, cost functions, and optimizers) are implemented manually. The goal is to provide a clear and deep understanding of how these models actually work.

The repository is divided into two main parts:
- **From-Scratch (Manual Implementation)**
- **PyTorch Implementations**

**Future updates:** Attention Mechanisms and Transformers will be added.

---

### Table of Contents

- [1. Deep Learning From Scratch (Manual Implementation)](#1-deep-learning-from-scratch-manual-implementation)
- [2. Deep Learning with PyTorch](#2-deep-learning-with-pytorch)
- [Practical Projects Summary](#practical-projects-summary)
- [Coming Next](#coming-next)
- [Contact](#contact)

---

### 1. Deep Learning From Scratch (Manual Implementation)

**Main Folder:** [Deep Learning From Scratch (manual implementation)](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation))

#### Multilayer Perceptron (MLP)
![Cost Functions](images/cost-functions.png)

- Manual forward and backward propagation
- Cost functions (MSE / LMS and Cross-Entropy)
- Optimizers (SGD, Momentum, AdaGrad, RMSprop, Adam)

📁 [Go to folder](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/1-%20Multilayer%20Perceptron(MLP))

**Optimizers Visualization:**

| Optimizer | Image |
|---------|-------|
| SGD | ![SGD](images/SGD.png) |
| SGD with Momentum | ![SGD Momentum](images/sgd-with-momentum.png) |
| AdaGrad | ![AdaGrad](images/adagrad.png) |
| RMSprop | ![RMSprop](images/rmsprop.png) |
| Adam | ![Adam](images/adam.png) |

#### Convolutional Neural Networks (CNNs)
![LeNet](images/LeNet.png)

- Manual implementation of Conv2d, Average Pooling, and Fully Connected layers
- Batch Normalization (1d & 2d)
- LeNet-5 architecture (with and without BatchNorm)

📁 [Go to folder](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/2-%20Covnvolutional%20Neural%20Netwroks%20(CNNs))

![Batch Normalization](images/batch-normalization.png)

#### Recurrent Neural Networks (RNNs)
![RNNs](images/Recurrent-Neural-Networks-(RNNs).png)

- Vanilla RNN and Bidirectional RNN
- LSTM and Bidirectional LSTM
- Full Backpropagation Through Time (BPTT)

📁 [Go to folder](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/3-%20Recurrent%20Neural%20Networks%20(RNNs))

![BiLSTM](images/BiLSTM.png)

---

### 2. Deep Learning with PyTorch

**Main Folder:** [Deep Learning-PyTorch](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch)

#### MLP
📁 [Go to folder](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch/1-%20MLP)

#### CNNs (Modern Architectures)
![AlexNet](images/alexnet.png)
![GoogLeNet](images/googleNet.png)
![NiN](images/NiN--Networks-in-Networks.png)
![ResNet](images/ResNet.png)

- LeNet-5, AlexNet, VGG, NiN, GoogLeNet, PlainNet, ResNet

📁 [Go to folder](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch/2-%20CNNs)

#### RNNs
📁 [Go to folder](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch/3-%20RNNs)

---

### Practical Projects Summary

#### Digit Classification
![BiLSTM Digits](images/digit-classification-using-BiLSTM.png)

#### Breast Cancer Classification
![Breast Cancer](images/breast-cancer.png)

#### Iris Classification
![Iris](images/iris.png)

#### EEG Signal Analysis
![EEG](images/eeg-signal-analysis.png)

#### Spam Detection
![Spam Detection](images/spam-detection.png)

#### Text Generation
![Text Generation](images/text-generation-using-RNNs.png)

| Project                              | Model(s) Used                  | Type              |
|--------------------------------------|--------------------------------|-------------------|
| House Price Prediction               | MLP                            | Regression        |
| Breast Cancer / Iris Classification  | MLP                            | Classification    |
| Digits Classification                | MLP, RNN, LSTM, BiLSTM         | Classification    |
| Air Quality Prediction (UCI)         | MLP, RNN, LSTM, GRU            | Time Series       |
| MNIST Digit Classification           | LeNet-5, AlexNet, VGG, ResNet  | Classification    |
| Epilepsy Detection from EEG          | GRU                            | Biomedical        |
| Spam Detection                       | LSTM                           | NLP               |
| Word Generation                      | LSTM                           | NLP               |

---

### Coming Next

- Attention Mechanisms
- Transformer Architecture

---

### Contact

- Website: [https://onlinebme.com](https://onlinebme.com)  
- YouTube: [https://www.youtube.com/@Mrcherloo](https://www.youtube.com/@Mrcherloo)  
- LinkedIn: [https://www.linkedin.com/in/mohammad-norizadeh-cherloo](https://www.linkedin.com/in/mohammad-norizadeh-cherloo)  
- Google Scholar: [Mohammad Norizadeh Cherloo](https://scholar.google.com/citations?user=fIKpYm8AAAAJ)  
- GitHub: [Mohammad-Norizadeh-Cherloo](https://github.com/Mohammad-Norizadeh-Cherloo)

---

An old man once told me:  
*"If you want to drive more easily in a city, first walk through that city on foot!"*

The same is true in Artificial Intelligence.  
If you want to use or improve algorithms more effectively, you should first implement them from scratch. Only then will you gain a deep and clear understanding of the algorithm and the problem it solves.

— Mohammad Norizadeh Cherloo
