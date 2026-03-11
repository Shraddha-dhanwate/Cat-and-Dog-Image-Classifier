# 🐱🐶 Cat vs Dog Image Classifier

## 📌 Project Overview

This project is a **Deep Learning-based Image Classification system** that identifies whether an image contains a **cat or a dog**.
The model is built using **Convolutional Neural Networks (CNN)** and trained on an image dataset containing cat and dog images.

The goal of this project is to demonstrate how **computer vision and deep learning** can be used to automatically classify images.

---

## 🚀 Features

* Classifies images as **Cat or Dog**
* Uses **Convolutional Neural Networks (CNN)**
* Image preprocessing using **ImageDataGenerator**
* Training and validation pipeline
* Model evaluation and prediction visualization
* Implemented using **TensorFlow/Keras**

---

## 🛠️ Tech Stack

* **Python**
* **TensorFlow / Keras**
* **NumPy**
* **Matplotlib**
* **OpenCV**
* **Jupyter Notebook**

---

## 📂 Project Structure

```
Cat-Dog-Classifier/
│
├── cats_and_dogs/
│   ├── train/
│   │   ├── cats/
│   │   └── dogs/
│   │
│   ├── test/
│
├── cat_dog_classifier.ipynb
├── README.md
```

---

## ⚙️ How It Works

1. **Data Preprocessing**

   * Images are resized and normalized.
   * Image generators are used to feed data into the model.

2. **Model Architecture**

   * Convolution Layers
   * MaxPooling Layers
   * Flatten Layer
   * Dense Layers
   * Output Layer (Binary Classification)

3. **Training**

   * Model trained using **binary crossentropy loss**
   * Accuracy used as the evaluation metric.

4. **Prediction**

   * The trained model predicts whether the input image is a **cat or dog**.

---

## 📊 Model Training

The model is trained using:

* **Batch Size:** 128
* **Epochs:** 15
* **Image Size:** 150 × 150

Training and validation accuracy are monitored during training.

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/cat-dog-classifier.git
```

### 2️⃣ Navigate to the project folder

```bash
cd cat-dog-classifier
```

### 3️⃣ Install dependencies

```bash
pip install tensorflow numpy matplotlib opencv-python
```

### 4️⃣ Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

## 📈 Future Improvements

* Apply **Data Augmentation**
* Use **Transfer Learning (MobileNet / ResNet)**
* Deploy the model as a **Web App using Streamlit**
* Improve dataset size for better accuracy

---

## 🎯 Learning Outcomes

Through this project I learned:

* Image preprocessing techniques
* CNN architecture design
* Training deep learning models
* Image classification using TensorFlow/Keras

---

## 👩‍💻 Author

**Shraddha**
AI / Machine Learning Enthusiast
