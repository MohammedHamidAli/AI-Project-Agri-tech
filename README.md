# 🌱 Agri-Tech Analyzer

**AI-Powered Plant Disease Diagnosis for Smart Farming**

---

## 📌 Overview
Agri-Tech Analyzer is a mobile application designed to help farmers diagnose plant diseases in real-time using **Convolutional Neural Networks (CNNs)** and **computer vision**. Built with **Kotlin** and integrated with **Google’s ML Kit**, the app empowers farmers to capture leaf images and receive immediate, actionable insights about crop health.

This project was developed under the **Human-Centered Design (HCD)** framework, ensuring accessibility, simplicity, and usability for farmers in rural environments.

---

## 🚀 Features
- **Real-time plant disease detection** from leaf images.
- **High accuracy (97%+)** achieved through CNN training on the Kaggle *Plant Village* dataset.
- **Mobile-first design** with Kotlin for Android.
- **ML Kit integration** for filtering non-leaf inputs.
- **Cloud-ready backend** using AWS SageMaker and S3 for scalability.
- **Offline support** with model quantization for rural connectivity.

---

## 🧑‍🤝‍🧑 Human-Centered Design
- **Empathy Mapping**: Focused on farmers with limited technical expertise.
- **User Journey**: Simple flow — capture/upload → validate → diagnose → recommendation.
- **Accessibility**: Works under variable lighting and low-connectivity conditions.

---

## 🛠️ Tech Stack
| **Component** | **Technology** |
|---------------|----------------|
| **Machine Learning** | TensorFlow, Keras, PyTorch, Google Colab |
| **Mobile Development** | Kotlin, Android Studio |
| **Validation** | Google ML Kit Image Labeling API |
| **Cloud Backend** | AWS SageMaker, S3 |
| **Version Control** | Git, GitHub |

---

## 📂 Dataset
- **Source**: [Plant Village Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)
- **Size**: ~87K RGB images
- **Classes**: 38 categories (healthy + diseased leaves)
- **Split**: 80/20 (train/validation) + test set

---

## 📱 App Flow
1. **Capture/Upload** a leaf image.
2. **Validation** via ML Kit (filters non-leaf inputs).
3. **Diagnosis** using CNN model.
4. **Results** displayed with confidence scores.
5. **Recommendations** for treatment.

---

## 📊 Results
- **Validation Accuracy**: ~97.11% (10 epochs).
- **Examples**:
  - Tomato Early Blight → 97.7% confidence
  - Corn Gray Leaf Spot → 91.9% confidence
  - Non-leaf rejection → 0.0% confidence

---

## 🧪 Challenges & Solutions
- **Flutter library conflicts** → Migrated to Kotlin.
- **Accuracy for untrained inputs** → Integrated ML Kit for pre-validation.
- **Connectivity issues** → Edge computing + model quantization.

---

## 🔮 Future Scope
- **Optimization**: Improve rare pathogen detection.
- **Branding**: Unique logo and identity.
- **Scalability**: Expand dataset to regional crop varieties.

---

## 📖 References
- Kaggle: *New Plant Diseases Dataset*
- Google Developers: *ML Kit Image Labeling API*
- AWS Documentation

---

## 👨‍💻 Author
**Mohammed Hamid M. Ali**  
Enrollment No: 92301733059-6EK2  
Marwadi University, Faculty of Engineering & Technology    
Instructor: Prof. C.D Parmar & Prof. Nishith Kotak  

---

## 📅 Submission
**Date:** May 5, 2026
