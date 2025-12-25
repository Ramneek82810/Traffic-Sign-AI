# 🚦Traffic Sign Recognition using Deep Learning

A Convolutional Neural Network (CNN)-based AI system designed to automatically recognize German traffic signs from images. This project leverages the GTSRB dataset to train a model that can assist in autonomous driving systems by accurately detecting and classifying traffic signs.
 
---
 
## 🧠 Key Features  

- 🧾 Recognizes and classifies over 40 different types of traffic signs
- 🖼️ Handles `.ppm` format images from the GTSRB dataset
- 🧠 Built using CNNs with multiple convolution and pooling layers 
- 📉 Outputs training loss and accuracy graphs for performance evaluation
- 📌 Visualizes predictions on actual sign images
- 🔁 Easily extendable to other datasets (e.g., LISA Traffic Sign Dataset) 

---
 
## 🎯 Real-World Applications

- 🚗 Self-driving cars and ADAS (Advanced Driver Assistance Systems)
- 📸 Traffic sign compliance monitoring via dashcams
- 🧠 Driver training and simulation software
- 📊 Intelligent Transport Systems (ITS)

---

## 🗂️ Dataset Overview: GTSRB

- 🎓 Source: [German Traffic Sign Recognition Benchmark](https://benchmark.ini.rub.de/gtsrb_news.html)
- 📁 Image Format: `.ppm`
- 🔢 43 classes of traffic signs
- 💡 Each image is labeled with the correct traffic sign class

---

## 🛠️ Technologies & Libraries Used

- **Python 3.13.5**
- **TensorFlow / Keras**
- **NumPy**
- **OpenCV** (optional for preprocessing)
- **Matplotlib** (for result visualization)
- **Sklearn** (for evaluation metrics)

---

## 📂 Project Structure

```
📁 Traffic-Sign-AI/
├── traffic.py          # Model training and prediction script
├── 0000x_xxxxx.ppm     # Image files from the dataset
└── README.md           # Project documentation
```

---

## ⚙️ How It Works

1. **Load Dataset**: Reads `.ppm` image files and associated labels
2. **Preprocessing**: Resizes images, normalizes pixel values
3. **Model Building**: Uses a CNN architecture with convolution, ReLU, max-pooling, dropout, and dense layers
4. **Training**: Optimized with categorical cross-entropy loss and Adam optimizer
5. **Evaluation**: Accuracy score, confusion matrix, and prediction visualization
6. **Prediction**: Uses trained model to identify traffic signs in unseen images

---

## 🚀 Getting Started

1. Clone the repository  
2. Install required libraries  
3. Run the main script

```bash

git clone https://github.com/Ramneek82810/Traffic-Sign-AI
cd Traffic-Sign-AI
pip install -r requirements.txt  # or install manually
python traffic.py
```

---

## 📊 Sample Output

- 📈 Training and validation accuracy over epochs
- ✅ Sample image with predicted and true label
- 🔁 Confusion matrix for multi-class evaluation

---

## 🔮 Future Improvements

- 📹 Add real-time webcam-based traffic sign detection
- 📱 Deploy as mobile app using TensorFlow Lite
- 🎥 Integrate with vehicle dashcam or Raspberry Pi
- 🧪 Hyperparameter tuning and data augmentation
