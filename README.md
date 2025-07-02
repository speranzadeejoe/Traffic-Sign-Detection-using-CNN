# Traffic-Sign-Detection-using-CNN
# 🚦 Traffic Sign Detection using CNN

This project uses a Convolutional Neural Network (CNN) to classify German traffic signs from the GTSRB dataset.

## 📊 Model Performance
- ✅ Test Accuracy: **99.29%**
- 🧠 Model: 3 Convolutional layers + MaxPooling + Dense layers
- 🔍 Dataset: German Traffic Sign Recognition Benchmark (GTSRB)

## 📁 Dataset
The dataset used is the GTSRB (German Traffic Sign Recognition Benchmark), available on [Kaggle](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign).

## 🧠 Model Architecture
- Conv2D (32 filters) + ReLU + MaxPooling
- Conv2D (64 filters) + ReLU + MaxPooling
- Conv2D (128 filters) + ReLU + MaxPooling
- Flatten → Dense(128) + Dropout → Dense(43 softmax)

## 🛠 Tools & Libraries
- TensorFlow / Keras
- NumPy
- OpenCV
- scikit-learn
- Matplotlib

## 📌 Highlights
- Achieved very high accuracy with minimal preprocessing
- Can be extended to real-time detection using webcam
- Efficient for embedded and mobile inference

## 🙌 Acknowledgements
- [Kaggle GTSRB Dataset](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)

---

Made with ❤️ by speranza deejoe 
