# Implementation-of-ML-model-for-image-classification
This project implements an image classification application using Convolutional Neural Networks (CNN) and pretrained MobileNetV2. It is designed to classify images from the CIFAR-10 dataset and provides a user-friendly interface using the Streamlit framework for real-time predictions. It balances high accuracy with computational efficiency.

## Key Features

- **Dual Model Support**:
  - **MobileNetV2 (ImageNet)**: Recognizes 1,000 different classes from the ImageNet dataset, including everyday objects, animals, and vehicles.
  - **Custom CIFAR-10 Model**: Specializes in classifying images into one of ten specific categories such as airplanes, automobiles, and birds.

- **Intuitive Interface**:
  - **Navigation Bar**: Seamlessly switch between MobileNetV2 and CIFAR-10 models using a sleek sidebar menu.
  - **Real-Time Classification**: Upload an image to receive immediate predictions with confidence scores.

- **Educational and Practical Use**:
  - Ideal for learning about deep learning models and their performance.
  - Useful for practical applications where image classification is needed.
 
### Technologies Used
  - Python
  - TensorFlow and Keras for deep learning.
  - Streamlit for creating an interactive web interface.
  - CIFAR-10 dataset for training and testing.

## Getting Started

### Prerequisites

- Python 3.7 or later
- A web browser

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/JayRathod341997/DeepLensX.git
   cd Implementation-of-ML-model-for-image-classification
2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
4. **Start the Streamlit app**:
    ```bash
    streamlit run app.py
5. **Open the app**: 
    The app will open in your default web browser. If not, navigate to http://localhost:8501

### Contributing
  Feel free to fork the repository, open issues, or submit pull requests to contribute to the project.

### Acknowledgements
- TensorFlow and Keras for deep learning frameworks.
-Streamlit for enabling a user-friendly interface.
-CIFAR-10 dataset for providing labeled data.

