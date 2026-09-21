# Image-Classification-Model-using-CNN
# CNN Image Classification – Deep Learning

## 📌 Project Overview

This project is part of the **L&T Edutech – Deep Learning from Production to Deployment** assignment.

The objective of this project is to implement a **Convolutional Neural Network (CNN)** for image classification. The model is trained on a dataset containing **50,000 training images** and **10,000 testing images**, where each image has a size of **32 × 32 pixels with 3 RGB color channels**.

The project covers the complete workflow from data preprocessing and CNN model development to training, evaluation, and visualization of results.

---

## 🎯 Objectives

* Understand the fundamentals of Convolutional Neural Networks.
* Load and preprocess an image dataset.
* Build a CNN model for image classification.
* Train the model using training data.
* Evaluate the model using testing data.
* Visualize training and validation performance.
* Analyze the final model performance.

---

## 📊 Dataset

The dataset contains:

| Dataset  | Number of Images | Image Size  |
| -------- | ---------------: | ----------- |
| Training |           50,000 | 32 × 32 × 3 |
| Testing  |           10,000 | 32 × 32 × 3 |

### Image Format

* Height: 32 pixels
* Width: 32 pixels
* Channels: 3
* Color format: RGB

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **TensorFlow**
* **Keras**
* **NumPy**
* **Matplotlib**
* **Scikit-learn**

---

## 🧠 CNN Architecture

The CNN model consists of convolutional, pooling, flattening, and fully connected layers.

```text
Input Image
     ↓
Convolutional Layer
     ↓
ReLU Activation
     ↓
Max Pooling
     ↓
Convolutional Layer
     ↓
ReLU Activation
     ↓
Max Pooling
     ↓
Flatten
     ↓
Dense Layer
     ↓
Output Layer
```

The convolutional layers extract important visual features from the images, while the pooling layers reduce the spatial dimensions. The dense layers perform the final classification.

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Preprocessing
   ↓
Data Normalization
   ↓
CNN Model Creation
   ↓
Model Compilation
   ↓
Model Training
   ↓
Validation
   ↓
Model Evaluation
   ↓
Visualization
   ↓
Final Results
```

---

## 📁 Project Structure

```text
CNN_Task_1/
│
├── CNN_Task_1.ipynb
├── README.md
├── CNN_Task_1_Report.pdf
│
├── screenshots/
│   ├── dataset.png
│   ├── model_summary.png
│   ├── training.png
│   ├── accuracy.png
│   └── prediction.png
│
└── results/
    ├── accuracy_loss.png
    └── confusion_matrix.png
```

---

## ⚙️ Installation

Install the required Python libraries using:

```bash
pip install tensorflow numpy matplotlib scikit-learn jupyter
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_LINK>
```

### 2. Open the project folder

```bash
cd CNN_Task_1
```

### 3. Start Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open

```text
CNN_Task_1.ipynb
```

### 5. Run all the cells

The notebook will:

1. Load the dataset.
2. Preprocess the images.
3. Create the CNN model.
4. Train the model.
5. Evaluate the model.
6. Generate accuracy and loss graphs.
7. Display prediction results.

---

## 📈 Model Evaluation

The model is evaluated using the testing dataset.

The following metrics are considered:

* Training Accuracy
* Validation Accuracy
* Testing Accuracy
* Training Loss
* Validation Loss

### Results

| Metric              | Result |
| ------------------- | -----: |
| Training Accuracy   |    XX% |
| Validation Accuracy |    XX% |
| Test Accuracy       |    XX% |

> Replace `XX%` with the actual values obtained after training the model.

---

## 📊
