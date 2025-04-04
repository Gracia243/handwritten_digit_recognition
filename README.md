# Handwritten Digit Recognition using CNN

This project is a **Handwritten Digit Recognition** system using **Convolutional Neural Networks (CNNs)**. It is implemented using **TensorFlow and Keras**.

## Features
- **Trains a CNN model** on the MNIST dataset.
- **Evaluates the model's accuracy** on test data.
- **Visualizes training history** using Matplotlib.
- **Displays sample predictions** from the test dataset.

## Installation
### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/handwritten-digit-recognition.git
cd handwritten-digit-recognition
```
### **2. Install Dependencies**
Ensure you have Python installed, then install the required libraries:
```bash
pip install tensorflow numpy matplotlib opencv-python
```

## Usage
### **Train and Test the Model**
Run the following command in a Jupyter Notebook script:
```python
python handwritten_recognition.ipynb
```
This will:
- Load and preprocess the MNIST dataset.
- Train a CNN model.
- Evaluate its accuracy.
- Display sample predictions.


## Model Architecture
- **Conv2D (32 filters, 3x3, ReLU activation)**
- **MaxPooling2D (2x2)**
- **Conv2D (64 filters, 3x3, ReLU activation)**
- **MaxPooling2D (2x2)**
- **Conv2D (64 filters, 3x3, ReLU activation)**
- **Flatten Layer**
- **Dense (64 neurons, ReLU activation)**
- **Dense (10 neurons, Softmax activation)**

## Results
The model achieves an accuracy of **98%+** on the MNIST test set.

## Screenshots
![Sample Predictions](https://github.com/user-attachments/assets/76a45aad-23ac-4461-88c7-53bd6c18a49e)


## License
This project is licensed under the [MIT License](LICENSE).

## Contributions
Feel free to fork the repository and submit a pull request if you want to improve the model or add new features.

## Contact
For any questions, open an issue in the repo.
