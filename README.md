# MNIST Digit Classification

## Project Description

MNIST Digit Classification using Deep Learning.

This project uses:

- TensorFlow
- Keras
- Artificial Neural Network

The project recognizes handwritten digits from **0 to 9** using the MNIST dataset.

The model processes **28 × 28 grayscale images**, trains on handwritten digits, and predicts the correct digit.

## Objective

- To recognize handwritten digits from 0 to 9.
- To build a Deep Learning model using TensorFlow and Keras.
- To preprocess and normalize image data.
- To train the model using the MNIST dataset.
- To evaluate the performance of the trained model.
- To visualize training and validation performance.
- To compare different neural network configurations.
- To predict handwritten digits and compare actual and predicted labels.

## Student Details

- **Name:** JEEVAN K L
- **Course:** B.Tech Computer Science and Engineering (AI & ML)
- **Semester:** 3rd Semester
- **UEN:** RTU24101CS004
- **College:** Rai Technology University, Bangalore

## Deep Learning Model

The project uses an **Artificial Neural Network (ANN)** built using TensorFlow and Keras.

### Model Layers

1. **Input Layer** – accepts 28 × 28 pixel images.
2. **Flatten Layer** – converts the 28 × 28 image into a 784-element vector.
3. **Dense Layer** – contains 128 neurons with ReLU activation.
4. **Output Layer** – contains 10 neurons representing digits 0 to 9.

## Activation Functions

### ReLU

The **ReLU (Rectified Linear Unit)** activation function is used in the hidden Dense layer.

It introduces non-linearity and helps the neural network learn patterns from handwritten digit images.

### Softmax

The **Softmax** activation function is used in the output layer.

It converts the output values into probabilities for the 10 possible digit classes and the class with the highest probability is selected as the prediction.

## Dataset

The project uses the **MNIST Handwritten Digit Dataset**.

- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels
- Classes: 0–9
- Image Type: Grayscale

## Data Preprocessing

The following preprocessing steps are performed:

- Loading the MNIST dataset.
- Exploring and displaying sample images.
- Normalizing pixel values between 0 and 1.
- Preparing the images for the neural network.
- Separating training and testing data.

## Model Training

The baseline neural network is trained using:

- **Optimizer:** Adam
- **Loss Function:** Sparse Categorical Crossentropy
- **Epochs:** 5
- **Batch Size:** 128
- **Validation Split:** 10%

## Model Evaluation

The trained model is evaluated using the MNIST test dataset.

The project includes:

- Test accuracy
- Test loss
- Training accuracy
- Validation accuracy
- Training loss
- Validation loss
- Actual vs predicted digit comparison

## Experiment

An additional experiment is performed by changing the neural network configuration.

The project compares different configurations, including:

- Baseline model with **128 neurons**
- 128 neurons with **Dropout**
- 64 neurons with **Dropout**

The validation accuracy of the different configurations is visualized and compared.

## Project Workflow

1. Load the MNIST Dataset
2. Explore Sample Images
3. Preprocess the Data
4. Normalize Pixel Values
5. Build the Neural Network
6. Apply ReLU and Softmax Activation Functions
7. Train the Model
8. Evaluate the Model
9. Visualize Training and Validation Results
10. Test Predictions on Handwritten Digits
11. Perform a Model Configuration Experiment
12. Compare Model Performance

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook / Google Colab

## Repository Contents

- `MNIST_Handwritten_Digit_Classification.ipynb` – Main Deep Learning notebook
- `README.md` – Project documentation
- `REPORT.pdf` – Project report
- `requirements.txt` – Required Python libraries

## Author

**JEEVAN K L**  
**RTU24101CS004**

B.Tech Computer Science and Engineering (AI & ML)  
Rai Technology University, Bangalore
