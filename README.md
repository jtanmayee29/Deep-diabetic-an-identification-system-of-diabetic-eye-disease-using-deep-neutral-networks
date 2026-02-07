# 🧠 Deep Diabetic: Identification System of Diabetic Eye Disease Using Deep Neural Networks

## 📌 Project Overview

**Deep Diabetic** is a deep learning–based medical image analysis system developed using **Python 3.7.0** to detect diabetic eye disease (Diabetic Retinopathy) from retinal fundus images. The system uses deep neural networks to automatically identify disease patterns and assist in early diagnosis.

This project helps in early detection, which can prevent vision loss by supporting doctors with AI-based screening.

---

## 🎯 Objectives

* Detect diabetic retinopathy using retinal images
* Provide automated disease classification
* Support early diagnosis through AI
* Reduce manual medical screening workload

---

## 🚀 Features

* 🧠 Deep Neural Network (CNN) based detection
* 🩺 Identifies stages of diabetic retinopathy
* 📷 Image upload for prediction
* 📊 Fast and accurate classification results
* 💻 Simple Python-based implementation

---

## 🛠️ Technologies Used

**Programming Language:**

* Python 3.7.0

**Libraries & Frameworks:**

* TensorFlow
* Keras
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Flask (for web interface, if used)

**Development Tools:**

* Jupyter Notebook / VS Code
* Git & GitHub

---

## 🧠 How It Works

1. Retinal fundus images are collected as input.
2. Images are preprocessed (resizing, normalization).
3. A Convolutional Neural Network (CNN) is trained using labeled datasets.
4. The trained model classifies images into categories such as:

   * Normal
   * Mild
   * Moderate
   * Severe
5. The system outputs the predicted result.

---

## 📂 Project Structure

```
Deep-Diabetic/
│
├── dataset/
│   ├── train/
│   └── test/
│
├── models/
│   └── model.h5
│
├── static/
│   └── uploads/
│
├── templates/
│   └── index.html
│
├── app.py
├── train_model.py
├── predict.py
└── README.md
```

---

## ⚙️ Installation & Setup

### Prerequisites

* Python 3.7.0 installed
* pip installed

### Install Required Libraries

```
pip install tensorflow==2.2.0 keras==2.3.1 numpy pandas matplotlib opencv-python scikit-learn flask
```

### Steps to Run the Project

1. Clone the repository:

```
git clone https://github.com/your-username/Deep-Diabetic.git
```

2. Navigate to the project folder:

```
cd Deep-Diabetic
```

3. Train the model:

```
python train_model.py
```

4. Run the application:

```
python app.py
```

5. Open the browser and go to:

```
http://127.0.0.1:5000/
```

---

## 📊 Dataset

This project uses retinal fundus image datasets for training and testing.

Common sources:

* Kaggle Diabetic Retinopathy Dataset
* EyePACS Dataset

---

## 🔮 Future Enhancements

* Improve accuracy using advanced CNN models
* Detect multiple eye diseases
* Deploy as a mobile application
* Cloud-based prediction system

---

## 👩‍💻 Author

**Name:** Jangala Tanmayee
**Course:** Computer Science Engineering
**Project Type:** Academic Project
**Technology:** Python 3.7.0, Deep Learning
**Domain:** AI in Healthcare

---

## 📜 License

This project is developed for academic and research purposes only.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
