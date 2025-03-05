# EMNIST-Handwritten-Character-Recognition
E(Extended)MNIST Handwritten Character Recognition using Deep Learning Methods (CNN and MLP)

## Scope of the Project and Discussion

### 3.1 Dataset and Preprocessing

1. The project will utilize the EMNIST dataset, which includes handwritten letters and digits.

2. Data preprocessing will involve normalization, reshaping, and augmentation techniques.

3. Splitting the dataset into training, validation, and test sets.

### 3.2 Model Development

1. A CNN model will be designed using convolutional layers, pooling layers, and fully connected layers.

2. An MLP model with multiple hidden layers and activation functions will be implemented.

3. Model hyperparameters will be tuned using techniques like RandomSearch().

### 3.3 Training and Evaluation

1. Both models will be trained using appropriate loss functions and optimizers.

2. Model evaluation will be conducted using metrics like accuracy, precision, recall, and F1-score.

3. Confusion matrices and learning curves will be used for model performance visualization.

### 3.4 Comparison and Analysis

1. CNN and MLP models will be compared based on classification performance and computational cost.

2. The impact of dataset size, network architecture, and training time will be analyzed.

3. Recommendations will be provided on the suitability of each model for real-world applications.



## Dataset procurement and details on the data

### The dataset and download link.

The dataset has been taken from the public dataset in kaagle.com. The link to the dataset is provided as follows:-
https://www.kaggle.com/datasets/crawford/emnist. The project was performed in the Balanced Dataset. The dataset is divided into emnist-balanced-train.csv and emnist-balanced-test.csv file.

### About the dataset

The EMNIST Balanced dataset is meant to address the balance issues in the ByClass and ByMerge datasets. It is derived from the ByMerge dataset to reduce misclassification errors due to capital and lower case letters and also has an equal number of samples per class. This dataset is meant to be the most applicable.

train: 112,800
test: 18,800
total: 131,600
classes: 47 (balanced)

## Installing the required libraries and other requirements.

Python version 3.8 or above. The project was performed in Python version 3.12.
Please use the resources.txt file to install the dependencies into your python environment using pip.

### Command to install the dependencies.

pip install -r resources.txt


### Authors - Aryan Agarwal, Sourav Surya Majumdar and Soumitra Chakraborty
