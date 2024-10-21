**Overview**

This repository contains the implementation of a Human Activity Recognition (HAR) system developed as part of my MSc dissertation. The project aims to automatically identify and interpret human actions in videos using machine learning and deep learning techniques. The system leverages a variety of algorithms including CNN, LSTM, RNN, and SVM, trained on the UCF101 dataset.

**Key Features**

Human Action Recognition (HAR) from video data.
Utilizes state-of-the-art deep learning models: CNN, LSTM, GRU, and more.
Implements feature extraction, data preprocessing, and evaluation metrics for model performance.
Designed to work with real-world noisy data, handling complex environments such as variable lighting, crowded backgrounds, and occlusion.

**Dataset**

The project uses the UCF101 dataset, which consists of 101 action classes and over 13,000 video clips. The dataset includes diverse activities categorized into five types:

Human-Object Interaction
Body-Motion Only
Human-Human Interaction
Playing Musical Instruments
Sports
For more details on the dataset, visit the official UCF101 page.

**Algorithms**

The following algorithms were implemented and evaluated:

Convolutional Neural Networks (CNN)
Recurrent Neural Networks (RNN) and Gated Recurrent Units (GRU)
Convolutional Long Short-Term Memory (ConvLSTM)
Support Vector Machine (SVM)
Random Forest Classifier
Each algorithm was tested using a variety of evaluation metrics such as accuracy, precision, recall, F1-score, and confusion matrices.

**Results**

The project evaluated multiple models on the UCF101 dataset, with ConvLSTM achieving the highest accuracy. Detailed performance metrics for each model are provided in the results/ directory.

**Future Work**

Extend the system to support real-time activity recognition.
Explore multi-modal fusion techniques for integrating sensor data and video streams.
Improve model robustness to handle edge cases like extreme lighting or occlusion.


**Acknowledgements**

Thanks to the contributors of the UCF101 dataset.
