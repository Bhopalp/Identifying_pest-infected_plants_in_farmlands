# 🌿 Identifying Pest Infected Plants in Farmlands

This is a **Streamlit-based web application** designed to identify plant diseases from uploaded images. The system uses a pre-trained TensorFlow model to classify plant images into one of 38 categories, including healthy plants and various diseases.

## 🚀 Features
- **Upload Images**: Users can upload an image of a plant leaf.
- **Real-Time Prediction**: The system analyzes the image and predicts the disease (or confirms if the plant is healthy).
- **User-Friendly Interface**: Simple and intuitive design for seamless interaction.
- **Fast and Accurate**: Utilizes a state-of-the-art machine learning model for efficient predictions.

## 📦 Dataset
The model is trained on a dataset consisting of approximately **87,000 RGB images** of healthy and diseased crop leaves. The dataset is divided into:
- **Training Set**: 70,295 images
- **Validation Set**: 17,572 images
- **Test Set**: 33 images

The dataset includes **38 classes**, covering various plant species and their associated diseases.

### Folder Structure
```
plant-disease-recognition/
├── app.py                  # Main Streamlit application code
├── trained_plant_disease_model.keras  # Pre-trained TensorFlow model
├── home_page.jpeg          # Image for the Home page
├── requirements.txt         # Python dependencies
└── README.md                # This file
```

## 🛠️ Model Details
- **Framework**: TensorFlow/Keras
- **Input Size**: 128x128 RGB images
- **Classes**: 38 (e.g., Apple Scab, Tomato Leaf Mold, etc.)
- **Model File**: `trained_plant_disease_model.keras`

## 📝 About the Project
This project aims to assist farmers, researchers, and enthusiasts in identifying pest infected plants early, enabling timely intervention to protect crops and ensure healthier harvests. The system is built using advanced machine learning techniques and provides accurate predictions in seconds.

## 🙏 Acknowledgments
- Dataset source: https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset
- Libraries used: [Streamlit](https://streamlit.io/), [TensorFlow](https://www.tensorflow.org/)

---

### **requirements.txt**
```plaintext
streamlit==1.22.0
tensorflow==2.12.0
numpy==1.23.5
Pillow==9.5.0
```

---

Let’s work together to make agriculture smarter and more sustainable! 🌱
