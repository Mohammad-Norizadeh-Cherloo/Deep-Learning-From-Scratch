# Deep Learning From Scratch

**Complete from-scratch implementations of core Deep Learning models with full manual forward & backward passes**

![Deep Learning Overview](images/overview.png)

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

#### 1. Deep Learning From Scratch (Manual Implementation)
- [Multilayer Perceptron (MLP)](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/1-%20Multilayer%20Perceptron(MLP))
  - [Cost Functions](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/1-%20Multilayer%20Perceptron(MLP)/1-%20Cost%20Functions)
    - [MLP with LMS (MSE)](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/1-%20Multilayer%20Perceptron(MLP)/1-%20Cost%20Functions/1-%20MLP-LMS)
    - [MLP with Cross-Entropy](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/1-%20Multilayer%20Perceptron(MLP)/1-%20Cost%20Functions/2-MLP-Cross%20Entropy)
  - [Optimizers](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/1-%20Multilayer%20Perceptron(MLP)/2-%20Optimizers)
    - [SGD](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/1-%20Multilayer%20Perceptron(MLP)/2-%20Optimizers/1-%20SGD)
    - [SGD with Momentum](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/1-%20Multilayer%20Perceptron(MLP)/2-%20Optimizers/2-%20SGD-Momentum)
    - [AdaGrad](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/1-%20Multilayer%20Perceptron(MLP)/2-%20Optimizers/3-%20AdaGrad)
    - [RMSprop](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/1-%20Multilayer%20Perceptron(MLP)/2-%20Optimizers/4-%20RMSprop)
    - [Adam](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/1-%20Multilayer%20Perceptron(MLP)/2-%20Optimizers/5-%20ADAM)

- [Convolutional Neural Networks (CNNs)](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/2-%20Covnvolutional%20Neural%20Netwroks%20(CNNs))
  - [LeNet-5 on Digits](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/2-%20Covnvolutional%20Neural%20Netwroks%20(CNNs)/project01_LeNet05_digits.ipynb)
  - [LeNet-5 + BatchNorm on Digits](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/2-%20Covnvolutional%20Neural%20Netwroks%20(CNNs)/project02_LeNet05_with_BN_digits.ipynb)
  - [LeNet-5 on MNIST](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/2-%20Covnvolutional%20Neural%20Netwroks%20(CNNs)/project03_LeNet05_MNIST.ipynb)
  - [LeNet-5 + BatchNorm on MNIST](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/2-%20Covnvolutional%20Neural%20Netwroks%20(CNNs)/project04_LeNet05_with_BN_MNIST.ipynb)

- [Recurrent Neural Networks (RNNs)](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/3-%20Recurrent%20Neural%20Networks%20(RNNs))
  - [Vanilla RNN – Air Quality](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/3-%20Recurrent%20Neural%20Networks%20(RNNs)/project01_RNN_air.ipynb)
  - [Vanilla RNN – Digits](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/3-%20Recurrent%20Neural%20Networks%20(RNNs)/project01_RNN_digits.ipynb)
  - [BiRNN – Digits](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/3-%20Recurrent%20Neural%20Networks%20(RNNs)/project02_BiRNN_digits.ipynb)
  - [LSTM – Air Quality](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/3-%20Recurrent%20Neural%20Networks%20(RNNs)/project02_LSTM_air.ipynb)
  - [LSTM – Digits](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/3-%20Recurrent%20Neural%20Networks%20(RNNs)/project03_LSTM_digits.ipynb)
  - [BiLSTM – Digits](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/3-%20Recurrent%20Neural%20Networks%20(RNNs)/project04_BiLSTMs_digits.ipynb)

#### 2. Deep Learning with PyTorch
- [MLP](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch/1-%20MLP)
  - [MLP – Digits](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning-PyTorch/1-%20MLP/project01_MLP_digits.ipynb)
  - [MLP – Air Quality](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning-PyTorch/1-%20MLP/project02_MLP_air.ipynb)

- [CNNs](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch/2-%20CNNs)
  - [LeNet-5 – MNIST](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning-PyTorch/2-%20CNNs/project01_Lent05_MNIST.ipynb)
  - [AlexNet – MNIST](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning-PyTorch/2-%20CNNs/project02_1_AlexNet_MNIST.ipynb)
  - [AlexNet (Modern) – MNIST](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning-PyTorch/2-%20CNNs/project02_2_AlexNet_modern_MNIST.ipynb)
  - [VGG – MNIST](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning-PyTorch/2-%20CNNs/project03_VGG_MNIST.ipynb)
  - [NiN – MNIST](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning-PyTorch/2-%20CNNs/project04_NiN_MNIST.ipynb)
  - [GoogLeNet – MNIST](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning-PyTorch/2-%20CNNs/project06_1_GoogleNet_2014_auxiliary_MNIST.ipynb)
  - [GoogLeNet (Modern) – MNIST](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning-PyTorch/2-%20CNNs/project06_2_GoogleNet_modern_MNIST.ipynb)
  - [PlainNet – MNIST](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning-PyTorch/2-%20CNNs/project07_LightPlainNet.ipynb)
  - [ResNet – MNIST](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/blob/main/Deep%20Learning-PyTorch/2-%20CNNs/project08_LightResNet.ipynb)

- [RNNs](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch/3-%20RNNs)
  - [RNN / GRU / LSTM – Digits & Air Quality](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch/3-%20RNNs)
  - [Signal Processing (EEG)](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch/3-%20RNNs/Signal%20Processing)
  - [Sentiment Analysis](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch/3-%20RNNs/sentiment%20analysis)
  - [Text Generation](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch/3-%20RNNs/text_generation)
---
### 1. Deep Learning From Scratch (Manual Implementation)

**Main Folder:** [Deep Learning From Scratch (manual implementation)](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation))

#### Multilayer Perceptron (MLP)
![MLP](images/mlp.png)

- Manual forward and backward propagation
- Cost functions (MSE / LMS and Cross-Entropy)
- Optimizers (SGD, Momentum, AdaGrad, RMSprop, Adam)

📁 [Go to folder](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/1-%20Multilayer%20Perceptron(MLP))

#### Convolutional Neural Networks (CNNs)
![CNN](images/cnn.png)

- Manual implementation of Conv2d, Average Pooling, and Fully Connected layers
- Batch Normalization (1d & 2d)
- LeNet-5 architecture (with and without BatchNorm)

📁 [Go to folder](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/2-%20Covnvolutional%20Neural%20Netwroks%20(CNNs))

#### Recurrent Neural Networks (RNNs)
![RNN](images/rnn.png)

- Vanilla RNN and Bidirectional RNN
- LSTM and Bidirectional LSTM
- Full Backpropagation Through Time (BPTT)

📁 [Go to folder](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning%20From%20Scratch%20(manual%20impelementation)/3-%20Recurrent%20Neural%20Networks%20(RNNs))

---

### 2. Deep Learning with PyTorch

**Main Folder:** [Deep Learning-PyTorch](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch)

#### MLP
📁 [Go to folder](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch/1-%20MLP)

#### CNNs
- LeNet-5, AlexNet, VGG, NiN, GoogLeNet, PlainNet, ResNet

📁 [Go to folder](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch/2-%20CNNs)

#### RNNs
- RNN, GRU, LSTM
- EEG Signal Processing, Sentiment Analysis, Text Generation

📁 [Go to folder](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch/3-%20RNNs)

---
### Practical Projects

![Projects](images/projects.png)

| Project                              | Model(s) Used                  | Type              |
|--------------------------------------|--------------------------------|-------------------|
| House Price Prediction               | MLP                            | Regression        |
| Breast Cancer / Iris Classification  | MLP                            | Classification    |
| Digits Classification                | MLP, RNN, LSTM, BiLSTM         | Classification    |
| Air Quality Prediction (UCI)         | MLP, RNN, LSTM, GRU            | Time Series       |
| MNIST Digit Classification           | LeNet-5 + BatchNorm            | Classification    |
| Epilepsy Detection from EEG          | GRU                            | Biomedical        |
| Spam Detection                       | LSTM                           | NLP               |
| Word Generation                      | LSTM                           | NLP               |

---

### Optimizers & Cost Functions

![Optimizers](images/optimizers.png)

**Cost Functions (from scratch):**
- Mean Squared Error (MSE)
- Binary Cross-Entropy
- Categorical Cross-Entropy

**Optimizers (from scratch + visualization):**
- SGD
- SGD with Momentum
- AdaGrad
- RMSprop
- Adam

---

### PyTorch Implementations

**Main Folder:** [Deep Learning-PyTorch](https://github.com/Mohammad-Norizadeh-Cherloo/Deep-Learning-From-Scratch/tree/main/Deep%20Learning-PyTorch)

Clean PyTorch versions of the same models are also provided for comparison and practical use:
- MLP, RNN, GRU, LSTM
- LeNet-5, AlexNet, VGG, NiN, GoogLeNet, ResNet
- Applied on MNIST, Digits, Air Quality, EEG, and text data

---

### Coming Next

- Attention Mechanisms
- Transformer Architecture

---

### Contact

- **Website:** [https://onlinebme.com](https://onlinebme.com)
- **YouTube:** [https://www.youtube.com/@Mrcherloo](https://www.youtube.com/@Mrcherloo)
- **LinkedIn:** [https://www.linkedin.com/in/mohammad-norizadeh-cherloo](https://www.linkedin.com/in/mohammad-norizadeh-cherloo)
- **Google Scholar:** [Mohammad Norizadeh Cherloo](https://scholar.google.com/citations?user=fIKpYm8AAAAJ)
- **GitHub:** [Mohammad-Norizadeh-Cherloo](https://github.com/Mohammad-Norizadeh-Cherloo)
