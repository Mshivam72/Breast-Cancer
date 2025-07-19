**Breast Cancer Histopathological Image Classification**

This project focuses on classifying breast cancer histopathological images into malignant and benign categories using deep learning techniques. We implemented and compared two Convolutional Neural Network (CNN) architectures: DenseNet-201 and VGG-16.

**Overview**

Breast cancer is one of the most common and serious diseases affecting women worldwide. Accurate and early diagnosis is essential for effective treatment. In this project, we used CNN-based models to automate the classification of breast tissue images into two classes:

Malignant (cancerous)

Benign (non-cancerous)

**Methodology**

The steps followed in this project include:

**Dataset Importing**

1. Loaded a labeled dataset of histopathological images.

2. Applied preprocessing such as resizing and normalization.

**Feature Extraction**

1. Converted image data into a format suitable for CNN input.

2. Used data augmentation to improve model performance and prevent overfitting.

**Model Building**

1. DenseNet-201: A deep CNN architecture known for its dense connectivity and efficient feature reuse.

2. VGG-16: A classic CNN with 16 layers, used here as a comparative baseline.

**Model Training and Evaluation**


Trained the models using standard techniques and evaluated them using classification metrics like accuracy, precision, recall, and confusion matrix.

**Technologies Used**

Python

TensorFlow / Keras

NumPy, Pandas

OpenCV (for image processing)

Matplotlib, Seaborn (for visualization)

**Results**
Both models performed well in classifying the images. DenseNet-201 showed slightly better performance compared to VGG-16.
| Model        | Accuracy | 
| ------------ | -------- |
| DenseNet-201 | 62%      |   
| VGG-16       | 77%      |

