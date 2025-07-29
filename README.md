[![Python](https://img.shields.io/badge/Python%203.11.9-red?logo=python&logoColor=fff)](#)
[![CUDA](https://img.shields.io/badge/CUDA_Toolkit-12.8-blue)](#)
[![cuDNN](https://img.shields.io/badge/cuDNN-9.8.0-blue)](#)
[![Torch](https://img.shields.io/badge/Torch-2.7.1_cuda128-blue)](#)

### Design and Train the **RNN**, **LSTM** and **Transformer** models with HAR Dataset and compare to each other

The **HAR Dataset** (Human Activity Recognition) is a widely-used dataset in the field of activity recognition. It is
most
commonly referred to as the UCI HAR Dataset, published by the University of California, Irvine (UCI).

🔹 Key Features:
It contains data collected from the accelerometer and gyroscope sensors of a Samsung Galaxy S II smartphone.

Data was gathered from 30 volunteers performing six different activities:

* Walking
* Walking Upstairs
* Walking Downstairs
* Sitting
* Standing
* Laying

The signals were sampled at 50Hz.

The dataset is divided into training and test sets.

🔹 Use Cases:
This dataset is frequently used in machine learning, deep learning, signal processing, and health monitoring
applications, especially for recognizing human daily activities to support smart healthcare, fitness tracking, and
elderly care.

---

* Loss function: CrossEntropyLoss
* Optimizer: SGD
* Momentum: 0.9

#### Selected the best Larning rate and the wight decay


* RNN:
    - Larning rate: 0.25
    - Weight decay: 1e-6
* LSTM:
    - Larning rate: 0.3
    - Weight decay: 1e-4
* Transformer:
    - Larning rate: 0.1
    - Weight decay: 1e-5

---

#### Compare the results:

##### Loss Train:
![loss_train.png](documentation/loss_train.png)

##### Loss Valid:
![loss_valid.png](documentation/loss_valid.png)

##### Accuracy Train:
![accuracy_train.png](documentation/accuracy_train.png)

##### Accuracy Valid:
![accuracy_valid.png](documentation/accuracy_valid.png)
