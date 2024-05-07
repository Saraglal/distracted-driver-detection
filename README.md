# distracted-driver-detection
This notebook contains code for detecting distracted driving behaviors using dashboard camera images. The project aims to improve road safety by automatically identifying drivers engaged in distracting activities, such as texting, using social media, or taking selfies while driving.

## Technologies Used
- Python 3.11
- TensorFlow
- NumPy
- OpenCV (cv2)
- Matplotlib

## Dataset
The dataset used in this project is provided by State Farm and is available on Kaggle. It consists of 2D dashboard camera images labeled with various driver behaviors, including attentive driving, seatbelt usage, and distracted activities. The dataset is divided into training and test sets. You can find it [here](https://www.kaggle.com/c/state-farm-distracted-driver-detection).

## Contents
- Data Preprocessing: The notebook starts with data preprocessing steps, including loading and augmenting the dataset using TensorFlow's `ImageDataGenerator`.
- Model Development:
  - **Baseline Model**: A simple CNN model is built using TensorFlow's Keras API.
  - **Improved Model**: A more sophisticated CNN model with additional layers and batch normalization is implemented to improve performance.
  - **Transfer Learning with VGG16**: Transfer learning using the pre-trained VGG16 model is explored to leverage its feature extraction capabilities.
- Training and Evaluation: The models are trained and evaluated using the training and validation datasets.
