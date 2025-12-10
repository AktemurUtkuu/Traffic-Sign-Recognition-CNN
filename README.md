# Traffic-Sign-Recognition-CNN

## 📌 Introduction
A robust **Traffic Sign Recognition (TSR)** system designed to detect and classify road signs with high accuracy using Deep Learning and Computer Vision techniques. This project aims to support Autonomous Vehicles and Advanced Driver Assistance Systems (ADAS) by providing real-time awareness of speed limits, warnings, and regulatory signs.

## ✨ Key Features
* **Real-time Detection:** Capable of processing video feeds to detect signs instantly.
* **High Accuracy:** Utilizes a Convolutional Neural Network (CNN) trained on the [GTSRB] dataset.
* **Multi-Class Classification:** Can identify and classify over [43] different types of traffic signs.
* **Robustness:** Works effectively under various lighting conditions.
* **User Interface:** Simple display showing the detected sign and confidence score.

## 🛠️ Technologies Used
* **Language:** Python
* **Computer Vision:** OpenCV
* **Deep Learning:**  PyTorch
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib

## 📂 Dataset
The model was trained using the **[German Traffic Sign Recognition Benchmark (GTSRB)]**.
* **Training Images:** [31367]
* **Test Images:** [12630]
* **Classes:** [43] classes (Stop, Speed Limit, Yield, etc.)