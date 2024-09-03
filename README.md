name: Potato Disease Classification Using CNN
description: |
  This project involves the design and implementation of a Convolutional Neural Network (CNN) to classify potato leaf images into three categories: potato_Early_blight, potato_Late_blight, and potato_Healthy. The CNN model achieves high performance, with a validation accuracy of 98% and a test accuracy of 94%, making it effective for real-time disease detection in potato crops.
  
  **Technologies Used:**
  - TensorFlow: For building and training the CNN model.
  - Keras: A high-level API within TensorFlow for model development.
  - Python: The programming language used for scripting and implementing the project.
  - NumPy and Pandas: For data manipulation and preprocessing.
  - Matplotlib: For data visualization and plotting training/validation accuracy and loss.
  - PlantVillage Dataset: The dataset used for training and testing the model.
  - Anaconda: For managing packages and environments, and running the development environment.
  - Jupyter Notebook: For interactive development and experimentation with the model.
  
  **Features:**
  - CNN Model: Built using TensorFlow and Keras, with layers for convolution, max pooling, and dense fully-connected layers.
  - Data Augmentation: Techniques such as random flipping and rotation are applied to improve model robustness.
  - Image Processing Pipeline: Efficient data pipeline for preprocessing and augmenting images, ensuring effective training and evaluation.
  
  **Installation:**
  To run this project, clone the repository and set up your environment using Anaconda:
  ```bash
  git clone https://github.com/anandbatchala/potatoleaf_disease_classifier.git
  cd potato-disease-classification
  conda create --name potato-disease python=3.8
  conda activate potato-disease
  pip install -r requirements.txt
