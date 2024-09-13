# Sign Language Recognition with Neural Network

Welcome to my Sign Language Recognition project! This project was developed as part of the **Girls Who Code Self-Paced Program (SPP) 2024**. I am passionate about this project because it leverages technology to address communication barriers. By improving sign language recognition, we can support individuals who rely on sign language to communicate, fostering inclusivity and accessibility.


## Project Overview

In this project, I developed a neural network model to classify American Sign Language (ASL) letters from images. The goal is to demonstrate how machine learning can be applied to real-world problems, particularly in helping individuals communicate more effectively.

### Key Features

- **Data Preprocessing**: Load and normalize the Sign Language MNIST dataset.
- **Model Training**: Build and train an `MLPClassifier` to recognize ASL letters.
- **Evaluation**: Assess model performance using accuracy metrics and a confusion matrix.
- **Visualization**: Plot histograms and sample images from the dataset to better understand the data.

## Files and Utilities

### `main.py`
This is the main script where the primary program is executed. It includes data loading, model training, and evaluation.

### `ClassViewer.py`
This utility program displays the first 10 images of a specified class. Run it by typing `python ClassViewer.py` in the terminal.

### `DataDumper.py`
This utility program shows the first 5 and last 5 rows, as well as the first two and last two columns, of the SignMNIST dataset. Execute it by typing `python DataDumper.py` in the terminal.

### `DisplayClassHist.py`
This script displays a histogram of the classes in the SignMNIST dataset. To run it, type `python DisplayClassHist.py` in the terminal.

### `ShowPixelGrid.py`
This utility displays a single image from the SignMNIST dataset with numerical pixel values overlaid. Change the row number in the `iloc` location to select which row of the dataset is displayed. Run it by typing `python ShowPixelGrid.py` in the terminal.

### `sign_mnist_13bal_test.csv`
This CSV file contains a test portion of a balanced sample with 13 images from each class in the SignMNIST dataset.

### `sign_mnist_13bal_train.csv`
This CSV file contains a training portion of a balanced sample with 13 images from each class in the SignMNIST dataset.


https://replit.com/@marthah48/Basic-Neural-Nets-Final-Challenge-Code-Martha-H?v=1
