# Multiclass Classification of Fashion MNIST using Keras (ANN Only)
## Objective
The goal of this project is to build a multiclass classification model using Keras with a TensorFlow backend to classify images of fashion items from the Fashion MNIST dataset. This project demonstrates how to preprocess image data, design and train a fully connected Artificial Neural Network (ANN) for image classification, and evaluate the model using standard performance metrics.

## Fashion MNIST Dataset
Fashion MNIST is a dataset of grayscale images, each of size 28x28 pixels, belonging to 10 different fashion categories. The dataset is designed to serve as a more challenging alternative to the well-known MNIST digits dataset. Each image in Fashion MNIST is labeled with one of the following categories:

1- T-shirt/top

2- Trouser

3- Pullover

4- Dress

5- Coat

6- Sandal

7- Shirt

8- Sneaker

9- Bag

10- Ankle boot

The dataset consists of 70,000 images in total:

1- **Training Set:** 60,000 images

2- **Test Set:** 10,000 images

## Instructions for Running the Code
1- **Install Dependencies:** Ensure all dependencies (listed below) are installed on your system.

2- **Download Dataset:** The Fashion MNIST dataset is automatically downloaded when you run the code.

3- **Run the Notebook:** Open the Jupyter Notebook and execute each cell sequentially to preprocess the data, build and train the model, evaluate its performance, and visualize results.

## Dependencies and Installation
This project uses Python and requires the following packages:

1- **numpy:** For array manipulations

2- **matplotlib:** For plotting graphs and displaying images

3- **seaborn:** For better-styled plots (specifically for confusion matrix visualization)

4- **scikit-learn:** For evaluation metrics like classification report and confusion matrix

5- **tensorflow (with keras):** For building and training the deep learning model

To install the dependencies, run the following command:

pip install numpy matplotlib seaborn scikit-learn tensorflow

## Expected Results and Model Performance
Upon training, the model should achieve a test accuracy of at least 90%. Key results include:

1- **Model Accuracy:** High accuracy on both the training and test sets, with performance monitored on validation data to prevent overfitting.

2- **Evaluation Metrics:** A comprehensive classification report with precision, recall, and F1-score for each class, along with a confusion matrix to visualize class-wise performance.

3- **Training and Validation Curves:** Graphs displaying the model’s loss and accuracy over epochs for both training and validation sets.

These outputs are visualized within the notebook to help analyze model performance, identify potential overfitting, and observe model improvement over time.