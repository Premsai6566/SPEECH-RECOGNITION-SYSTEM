# SPEECH-RECOGNITION-SYSTEM
COMPANY: CODTECH IT SOLUTIONS

NAME: SITHARAM PREM SAI

INTERN ID: CODHC71

DURATION: 8 WEEKS

MENTOR: NEELA SANTHU

##Description:
MNIST Handwritten Digit Classification using CNN (PyTorch)
A Convolutional Neural Network (CNN) for classifying handwritten digits (0-9) from the MNIST dataset using PyTorch.
Features
 Loads and preprocesses the MNIST dataset (normalization, batching).
 Implements a CNN with two convolutional layers and fully connected layers.
 Uses Adam optimizer and CrossEntropy loss for training.
 Evaluates model performance on test data.
 Visualizes predictions with matplotlib.
 Project Structure
graphql
 mnist-cnn
│── data/                   # Directory where MNIST data is stored
│── mnist_cnn.py            # Main script for training and evaluation
│── requirements.txt        # Dependencies
│── README.md               # Project documentation
 Installation & Usage
 Clone the Repository
git clone https://github.com/your-username/mnist-cnn.git
cd mnist-cnn
 Install Dependencies
pip install -r requirements.txt
 Train & Evaluate the Model
python mnist_cnn.py
 Results
 Training Accuracy: ~99%
 Test Accuracy: ~98%
Example Predictions
 Model Architecture
Conv Layer 1 → 32 filters, ReLU, MaxPool
Conv Layer 2 → 64 filters, ReLU, MaxPool
FC Layer 1 → 128 neurons, ReLU
FC Layer 2 → 10 neurons (Output)
