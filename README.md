# 🧠 Brain Tumor Detection using CLAHE, CNN, Genetic Algorithm, SVM and EfficientNetB0

## 📌 Overview
Brain tumors are one of the most serious neurological diseases, and early detection plays a critical role in effective treatment. This project proposes a hybrid machine learning and deep learning framework for accurate brain tumor classification from MRI images.

The proposed approach combines image enhancement, deep feature extraction, evolutionary feature optimization, and machine learning classification to improve detection performance.

The pipeline integrates:

- **CLAHE (Contrast Limited Adaptive Histogram Equalization)** for image enhancement  
- **Convolutional Neural Networks (CNN)** for feature extraction  
- **Genetic Algorithm (GA)** for optimal feature selection  
- **Support Vector Machine (SVM)** for classification  
- **EfficientNetB0** for deep learning comparison  

The system classifies MRI brain images into four categories:

- Glioma Tumor  
- Meningioma Tumor  
- Pituitary Tumor  
- No Tumor  

---

# 🧠 Project Pipeline

```
MRI Brain Image
      ↓
CLAHE Image Enhancement
      ↓
CNN Feature Extraction
      ↓
Genetic Algorithm Feature Selection
      ↓
SVM Classification
      ↓
Tumor Type Prediction
```

---

# 🎯 Objectives

The main objectives of this project are:

- Improve MRI image quality using **CLAHE enhancement**
- Extract meaningful features using **CNN**
- Reduce redundant features using **Genetic Algorithm**
- Classify brain tumor types using **Support Vector Machine**
- Compare performance with **EfficientNetB0 deep learning model**

---

# 📂 Dataset

The dataset consists of MRI brain tumor images divided into four classes:

| Class | Description |
|------|-------------|
| Glioma | Tumor originating from glial cells |
| Meningioma | Tumor formed in meninges |
| Pituitary | Tumor in pituitary gland |
| No Tumor | Normal brain MRI |

### Dataset Structure

```
Dataset
│
├── Training
│   ├── glioma_tumor
│   ├── meningioma_tumor
│   ├── pituitary_tumor
│   └── no_tumor
│
└── Testing
    ├── glioma_tumor
    ├── meningioma_tumor
    ├── pituitary_tumor
    └── no_tumor
```

---

# 🧪 Methods Used

## 1️⃣ CLAHE Enhancement
Contrast Limited Adaptive Histogram Equalization improves local contrast in MRI images and enhances tumor visibility.

Benefits:
- Improves contrast
- Highlights tumor regions
- Enhances feature extraction performance

---

## 2️⃣ Convolutional Neural Network (CNN)

CNN is used for automatic feature extraction from MRI images.

Typical layers used:

- Convolution Layer
- Max Pooling Layer
- Flatten Layer
- Dense Layer

The extracted deep features are used for further processing.

---

## 3️⃣ Genetic Algorithm (GA)

Genetic Algorithm is used for **feature selection**.

Steps involved:

1. Population Initialization  
2. Fitness Evaluation  
3. Selection  
4. Crossover  
5. Mutation  
6. Feature Optimization  

This helps in selecting the most relevant features from CNN outputs.

---

## 4️⃣ Support Vector Machine (SVM)

SVM is used as the final classifier for tumor detection.

Advantages:

- Works well with high-dimensional data
- Effective for small datasets
- Provides robust classification boundaries

---

## 5️⃣ EfficientNetB0

EfficientNetB0 is used as a deep learning comparison model to evaluate performance against the hybrid approach.

---

# 📊 Model Comparison

| Model | Description |
|------|-------------|
| CNN | Deep learning classifier |
| CNN + SVM | CNN feature extraction + SVM classification |
| CNN + GA + SVM | Feature optimization using Genetic Algorithm |
| EfficientNetB0 | Pretrained deep learning architecture |

---

# ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- Scikit-Learn
- OpenCV
- NumPy
- Matplotlib
- DEAP (Genetic Algorithm Library)
- Google Colab / Jupyter Notebook

---

# 🚀 Installation

Clone the repository:

```
git clone https://github.com/your-username/BrainTumor-Detection.git
```

Install dependencies:

```
pip install tensorflow
pip install opencv-python
pip install scikit-learn
pip install numpy
pip install matplotlib
pip install deap
```

---

# ▶️ How to Run

1. Open the Jupyter Notebook:

```
Brain_Tumor(SVM,CNN,GA,EffecientnetB0,Clahe_Enhancement).ipynb
```

2. Mount Google Drive (if using Google Colab)

3. Load dataset paths

4. Run all cells sequentially

---

# 📈 Expected Output

The model predicts one of the following classes:

- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor
- No Tumor

Evaluation metrics include:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# 📑 Research Contribution

This research proposes a **hybrid AI-based framework** that combines:

- Image enhancement  
- Deep learning feature extraction  
- Evolutionary feature selection  
- Machine learning classification  

to improve brain tumor detection accuracy from MRI images.

---

# 📚 Applications

- Medical image analysis
- Computer-aided diagnosis
- Brain tumor screening systems
- Healthcare AI systems

---

# 👨‍💻 Author

**Gautam Kumar B**  
B.Tech Computer Science Engineering  

Research Interests:

- Artificial Intelligence  
- Machine Learning  
- Deep Learning  
- Medical Image Processing  

---

# 📜 License

This project is intended for **research and educational purposes**.
