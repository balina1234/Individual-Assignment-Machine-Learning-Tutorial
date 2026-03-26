# Individual-Assignment-Machine-Learning-Tutorial
# Flower Image Classification using CNN and Transfer Learning with EfficientNetB0 (Fine-Tuning)


##  Overview
This project demonstrates an end-to-end image classification pipeline using deep learning techniques. It compares a baseline Convolutional Neural Network (CNN) with a transfer learning approach using EfficientNetB0, including fine-tuning.

The objective is to show how transfer learning improves accuracy, generalisation, and training efficiency compared to models trained from scratch.

---

##  Features
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Baseline CNN model (from scratch)  
- Transfer Learning using EfficientNetB0  
- Fine-tuning for improved performance  
- Model evaluation (Accuracy, Precision, Recall, F1-score)  
- Confusion matrix and prediction visualisation  

---

##  Dataset
Flowers Dataset from Kaggle:  
https://www.kaggle.com/datasets/nadyana/flowers  

The dataset contains 7 flower classes:
- Rose  
- Sunflower  
- Tulip  
- Daisy  
- Bellflower  
- Dandelion  
- Lotus  

Each class contains approximately 1600 images, making it a balanced dataset.

---

##  Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

##  Models Implemented

### 1. Baseline CNN
- 3 Convolutional layers  
- MaxPooling layers  
- Dense layer with Dropout  
- Accuracy: ~69%

---

### 2. EfficientNetB0 (Transfer Learning)
- Pre-trained on ImageNet  
- Frozen base layers  
- Custom classification head  
- Accuracy: ~95%

---

### 3. Fine-Tuned EfficientNetB0
- Last 50 layers unfrozen  
- Low learning rate (1e-5)  
- Accuracy: ~96%

---

##  Model Performance

| Model                     | Accuracy |
|--------------------------|----------|
| Baseline CNN             |  69%     |
| EfficientNet (Frozen)    |  95%     |
| Fine-Tuned EfficientNet  |  96%     |

---

##  Key Insights
- Transfer learning provides a significant performance improvement  
- Fine-tuning further enhances model accuracy and generalisation  
- Pre-trained models outperform CNNs trained from scratch  
- Feature quality is more important than model complexity  

---

##  How to Run

1. Clone the repository:
git clone https://github.com/your-username/Individual-Assignment-Machine-Learning-Tutorial.git  
cd Individual-Assignment-Machine-Learning-Tutorial  

2. Install dependencies:
pip install -r requirements.txt  

3. Run the notebook:
jupyter notebook  

---

## 📸 Results
- Accuracy and Loss plots  
- Confusion matrices  
- Prediction visualisations  






---

## ⭐ If you like this project
Give it a star on GitHub!
