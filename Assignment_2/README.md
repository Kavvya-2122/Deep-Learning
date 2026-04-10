# 🌍 Remote Sensing Image Classification using Pre-trained Deep Learning Models

## 📌 Project Overview
This project focuses on **land use and land cover classification** using **pre-trained deep learning models** on the **EuroSAT dataset**. The goal is to leverage **transfer learning** to achieve high accuracy with minimal training time.

---

## 🎯 Objectives
- Apply **pre-trained CNN models** for image classification
- Perform **data preprocessing and augmentation**
- Implement **fine-tuning strategies**
- Evaluate model performance using standard metrics
- Visualize feature maps and training behavior

---

## 📂 Dataset
- **Dataset Used:** EuroSAT RGB Dataset  
- **Source:** Zenodo  
- **Classes (10):**
  - AnnualCrop
  - Forest
  - HerbaceousVegetation
  - Highway
  - Industrial
  - Pasture
  - PermanentCrop
  - Residential
  - River
  - SeaLake

### ⚙️ Dataset Processing
- Downloaded dataset (~95MB)
- Extracted and structured into class folders
- Created a **balanced subset (5%)** for faster training
- Organized into training/validation sets

---

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- HuggingFace Datasets

---

## ⚙️ Workflow

### 1️⃣ Install & Import Libraries
- TensorFlow
- Matplotlib
- Seaborn
- NumPy

---

### 2️⃣ Dataset Preparation
- Download EuroSAT dataset
- Extract ZIP file
- Handle dynamic folder structure
- Create smaller balanced dataset

---

### 3️⃣ Exploratory Data Analysis (EDA)
- Visualize sample images
- Analyze class distribution

---

### 4️⃣ Preprocessing Pipeline
- Image resizing
- Normalization
- Data augmentation

---

### 5️⃣ Model Building (Transfer Learning)
Used pre-trained CNN models:
- Feature extraction using frozen layers
- Custom classification head added

---

### 6️⃣ Feature Map Visualization
- Visualized intermediate CNN layers
- Understood feature extraction patterns

---

### 7️⃣ Fine-Tuning
- Unfroze top layers of the model
- Reduced learning rate
- Increased epochs for better performance

---

### 8️⃣ Training
- Trained model on processed dataset
- Monitored:
  - Loss
  - Accuracy

---

### 9️⃣ Evaluation
- Evaluated model on validation/test data
- Metrics:
  - Accuracy
  - Confusion Matrix

---

## 📊 Results
- Achieved high classification accuracy using transfer learning
- Fine-tuning improved performance significantly
- Model generalized well on unseen data

---

## 📈 Visualizations
- Training vs Validation Accuracy
- Training vs Validation Loss
- Confusion Matrix
- Feature Maps

---

## 🚀 How to Run

### 1️⃣ Clone Repository
```bash
git clone <your-repo-link>
cd <repo-folder>
