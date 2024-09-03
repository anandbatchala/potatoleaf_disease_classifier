# Potato Disease Classification Using CNN

## Description
This project implements a Convolutional Neural Network (CNN) to classify potato leaf images into three categories: **Early Blight**, **Late Blight**, and **Healthy**. The model achieves **98% validation accuracy** and **94% test accuracy**, making it highly effective for real-time disease detection. This tool supports improved agricultural management by accurately identifying potato leaf diseases.

  ## Technologies Used
  - **TensorFlow**: Framework for building and training the CNN model.
  - **Keras**: High-level API in TensorFlow for model development.
  - **Python**: Programming language used for implementation.
  - **NumPy & Pandas**: For data manipulation and preprocessing.
  - **Matplotlib**: For visualizing training and validation metrics.
  - **PlantVillage Dataset**: Source of images for training and testing.
  - **Anaconda**: Environment management and package handling.
  - **Jupyter Notebook**: Interactive development and experimentation.

  ## Features
  - **Robust CNN Architecture**: Designed with multiple convolutional and pooling layers.
  - **Data Augmentation**: Includes random flips and rotations to enhance model generalization.
  - **Efficient Data Pipeline**: Optimized for preprocessing and augmenting images.

  ## Getting Started
  To run this project:
  1. Clone the repository:
     ```bash
     git clone https://github.com/anandbatchala/potatoleaf_disease_classifier.git
     ```
  2. Navigate to the project directory and set up the environment:
     ```bash
     cd potatoleaf_disease_classification
     conda create --name potato-disease python=3.8
     conda activate potato-disease
     ```
  3. Place the PlantVillage dataset in the `data` directory.
  4. Run the provided Jupyter Notebook or Python script to train and evaluate the model.

  ## Contribution
  Contributions are welcome! Please feel free to open issues or submit pull requests.

