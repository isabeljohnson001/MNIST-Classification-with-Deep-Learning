# MNIST-Classification-with-Deep-Learning

The MNIST dataset is a widely used dataset in the field of machine learning and computer vision. It consists of a large collection of 28x28 grayscale images of handwritten digits (0-9). The dataset is commonly used as a benchmark for developing and evaluating algorithms in image classification tasks. The MNIST dataset is often used as a starting point for learning and experimenting with image classification algorithms and deep learning models. It provides a relatively simple and well-defined task, making it easier to understand and evaluate the performance of different approaches.
<pre>
Domain             : Computer Vision, Machine Learning
Sub-Domain         : Deep Learning, Image Recognition
Techniques         : Deep Convolutional Neural Network
Application        : Image Recognition, Image Classification
</pre>

### Description
<pre>
Kannada is a language spoken predominantly by people of Karnataka in southwestern India. The language has roughly 45 million native speakers and is written using the Kannada script.
1. Detected 10 Kannada (Kannada is a language spoken predominantly by people of Karnataka in southwestern India. The language has roughly 45 million native speakers) digits from images with Custom Convolutional Neural Network.
2. Built a simple custom convolutional neural network with few 2D convolutional, Maxpool and 1 dense layer with around 888K trainable params.
3. After 27 training iterations, attained testing accuracy of 97.70% and loss 0.03 on 60K (12MB+) OCR image dataset.
</pre>

### Objective:

The goal is to train a deep learning model to classify these handwritten digits accurately

#### Dataset
<pre>
Dataset Name     : Kannada MNIST
Dataset Link     : <a href=https://www.kaggle.com/c/Kannada-MNIST>Kannada-MNIST (Kaggle)</a>
                 : <a href=https://github.com/vinayprabhu/Kannada_MNIST (GitHub Original Dataset)</a>
                 
Original Paper   : <a href=https://arxiv.org/abs/1908.01242>Kannada-MNIST: A new handwritten digits dataset for the Kannada language</a> 
                   Authors: Vinay Uday Prabhu 
</pre>

### Dataset Details
<pre>
Dataset Name            : Kannada MNIST
Number of Class         : 10
</pre>

| Dataset Subtype | Number of Image | Size of Images (GB/Gigabyte) |
| :-------------- | --------------: | ---------------------------: |
| **Total**       | 40,000          | 12 MB                        |
| **Training**    | 34,000          | 10.2 MB                      |
| **Validation**  | 6,000           | 1.8 MB                       |
| **Testing**     | 44,004          |                       |


### Model and Training Prameters
| Current Parameters   | Value                                                       |
| :------------------- | ----------------------------------------------------------: |
| **Base Model**       | Custom CNN                                                  |
| **Optimizers**       | Adam                                                        |
| **Loss Function**    | Categorical Crossentropy                                    |
| **Learning Rate**    | 0.0001                                                      |
| **Batch Size**       | 128                                                         |                                     
| **Number of Epochs** | 40                                                          |


### Model Performance Metrics (Prediction/ Recognition / Classification)
| Dataset              | Training       | Validation    | Test      |                                 
| :------------------- | -------------: | ------------: | --------: |
| **Accuracy**         | 99.74%         | 98.93%        | ---    |
| **Loss**             | 0.0205         | 0.0663        | ---       |
| **Precision**        | ---            | ---           | ---       |
| **Recall**           | ---            | ---           | ---       |
| **Roc-Auc**          | ---            | ---           | ---       |


### Other Experimented Model and Training Prameters
| Parameters (Experimented) | Value                                                  |
| :------------------------ | -----------------------------------------------------: |
| **Base Models**           | Custom Convolutional Neural Network wwith 888K params  |
| **Optimizers**            | Adam                                                   |
| **Loss Function**         | Categorical Crossentropy                               |
| **Learning Rate**         | 0.01, 0.001, 0.0001                                    |
| **Batch Size**            | 32, 64, 96, 128, 256                                   |                                     
| **Number of Epochs**      | 40 - 50                                               |

### Visualization
#### Class Distribution: 
<kbd>
<img src=https://github.com/isabeljohnson001/MNIST-Classification-with-Deep-Learning/blob/main/class-dist.png>
</kbd>

#### Model Performance: 
<kbd>
<img src=https://github.com/isabeljohnson001/MNIST-Classification-with-Deep-Learning/blob/main/model_performance.png>
</kbd>

#### Tools / Libraries
<pre>
Languages               : Python
Tools/IDE               : Jupyter
Libraries               : Keras
</pre>

#### Dates
<pre>
Duration                : June 2023 
Current Version         : v1.0.0.10
Last Update             : 06.09.2023
</pre>

