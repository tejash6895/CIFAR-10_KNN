# CIFAR-10 Dataset Exploration and KNN Classification

This Jupyter Notebook documents the journey of exploring the CIFAR-10 dataset and implementing a K-Nearest Neighbors (KNN) classifier for image classification tasks. CIFAR-10 is a popular dataset consisting of 60,000 32x32 color images across 10 different classes, with 6,000 images per class.

## Overview

### 1. Dataset Loading and Exploration
   - Load the CIFAR-10 dataset.
   - Understand its structure and content.
   - Visualize sample images from different classes.

### 2. Data Preprocessing
   - Prepare the dataset for training and testing.
   - Normalize the data.
   - Split the dataset into training and testing sets.

### 3. Baseline Model
   - Implement a basic KNN classifier as a starting point.
   - Evaluate the baseline model's performance and accuracy.

### 4. Hyperparameter Tuning
   - Experiment with different hyperparameters for KNN.
   - Document the results and performance improvements.

### 5. Data Augmentation
   - Apply data augmentation techniques.
   - Observe the impact on model accuracy.

### 6. Model Evaluation
   - Evaluate the final KNN classifier's performance on the test dataset.
   - Report the achieved accuracy.

## How to Use

1. Clone the Repository: https://github.com/tejash6895/CIFAR-10_KNN/tree/main
2. cd cifar-10-knn-exploration


2. Set Up the Environment:
- Install required Python packages:
  ```
  pip install opencv-python matplotlib numpy scikit-learn
  ```

3. Specify the Dataset Path:
- Replace `/path/to/cifar-10-python.tar.gz` in the code with the actual path to your CIFAR-10 dataset.

4. Run the Code:
- Run the Jupyter Notebook cells for loading, preprocessing, training, and evaluating the KNN classifier.

5. Experiment and Reflect:
- Experiment with hyperparameters and data augmentation to improve model accuracy.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

