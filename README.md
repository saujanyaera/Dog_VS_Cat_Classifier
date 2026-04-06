# 🐶🐱 Dog vs Cat Image Classifier (CNN)

A deep learning project that classifies images as **Dog** or **Cat** using a **Convolutional Neural Network (CNN)** built with **TensorFlow and Keras**.

The model is trained on a labeled image dataset and learns visual features such as shapes, edges, and textures to distinguish between the two classes.

---

# 📌 Project Overview

This project demonstrates how to build an **image classification model** using deep learning techniques.

The workflow includes:

1. Loading and preprocessing image datasets
2. Building a Convolutional Neural Network (CNN)
3. Training the model on labeled data
4. Evaluating model performance
5. Predicting whether an image contains a dog or a cat

The goal of the project is to understand the **fundamentals of computer vision and CNN architectures**.

---

# 🧠 Model Architecture

The CNN model consists of the following layers:

* **Conv2D Layers** – Extract image features such as edges and textures
* **Batch Normalization** – Stabilizes and speeds up training
* **MaxPooling Layers** – Reduces spatial dimensions
* **Flatten Layer** – Converts feature maps into a vector
* **Fully Connected Dense Layers** – Learns high-level patterns
* **Dropout Layers** – Helps prevent overfitting
* **Sigmoid Output Layer** – Produces probability for binary classification

Loss Function:

* Binary Crossentropy

Optimizer:

* Adam

Evaluation Metric:

* Accuracy

---

# 📂 Dataset

The model was trained on a dataset containing images of **dogs and cats**.

Dataset structure:

training_set/
    cats/
    dogs/

test_set/
    cats/
    dogs/

Images are resized to **256 × 256 pixels** before training.

---

# ⚙️ Technologies Used

* Python
* TensorFlow
* Keras
* OpenCV
* Google Colab

---

# 🚀 How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/your-username/dog-vs-cat-classifier.git
cd dog-vs-cat-classifier
```

### 2. Install dependencies

```
pip install tensorflow opencv-python numpy matplotlib
```

### 3. Run the notebook

Open the notebook in **Jupyter Notebook or Google Colab** and run all cells.

---

# 🔍 Prediction Example

The model predicts the probability of an image being a dog or cat.

Example:

```
Prediction: Dog
Probability: 0.12
```

If probability > 0.5 → Cat
If probability < 0.5 → Dog

---

# 📊 Learning Outcomes

This project helped in understanding:

* How Convolutional Neural Networks work
* Image preprocessing techniques
* Overfitting and regularization (Dropout, L2)
* Batch Normalization
* Training deep learning models using TensorFlow/Keras

---

# 📌 Future Improvements

Possible improvements for this project:

* Data augmentation
* Transfer learning (ResNet, EfficientNet, MobileNet)
* Model deployment using FastAPI
* Building a web interface for image upload

---

# 👨‍💻 Author

Saujanya Bhattarai

