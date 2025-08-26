# 🛰️ Remote Sensing Image Analysis using Deep Learning  

![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python)  ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow) ![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red?logo=keras) ![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv) ![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24%2B-yellowgreen?logo=scikit-learn). ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)  

---

## 📑 Table of Contents  
1. [📌 Overview](#-overview)  
2. [🎯 Objectives](#-objectives)  
3. [📂 Dataset](#-dataset)  
4. [🏗️ System Architecture](#-system-architecture)  
5. [🧮 Model Performance](#-model-performance)  
6. [⚙️ Technologies Used](#-technologies-used)  
7. [🚀 Future Enhancements](#-future-enhancements)  
8. [📊 Results](#-results)    
9. [📜 License](#-license)  

---

## 📌 Overview  
This project implements **deep learning techniques** for automated analysis of **high-resolution remote sensing imagery**.  
By combining **ResNeXt-50 (CNN)** for spatial feature extraction and **LSTM** for temporal sequence modeling, the system achieves **95% accuracy** in detecting and classifying objects from aerial images.  

---

## 🎯 Objectives  
- Automate **object detection** in satellite and aerial imagery.
- Accurately classify objects into **5 categories**: Car, Boat, Tree, Vegetation, and Aeroplane .
- Improve detection **accuracy, speed, and scalability** compared to traditional methods 
- Enable applications in **environmental monitoring, surveillance, and urban planning**

---

## 📂 Dataset  
- **Name:** RSSOD (Remote Sensing Small Object Detection)  .
- **Size:** 2,000+ high-resolution aerial images  .
- **Classes:** (5 Classes) : Car, Aeroplane, Vegetation, Tree, Boat . 
- **Annotations:** Includes bounding boxes for object detection .
- **Kaggle Link** 

---

## 🏗️ System Architecture  
1. **Dataset Upload & Preprocessing**  
2. **Feature Extraction (ResNeXt-50)**  
3. **Temporal Analysis (LSTM)**  
4. **Prediction & Evaluation**  

---

## 🧮 Model Performance  
- **Accuracy:** ~95%  
- **Precision:** High across all classes  
- **Recall & F1-Score:** Balanced and reliable  
- **Efficiency:** Detection speed improved by **40%**, manual annotation reduced by **60%**  

---

## ⚙️ Technologies Used  
- **Programming Language:** Python  
- **Libraries & Frameworks:** TensorFlow, Keras, OpenCV, NumPy, Matplotlib, scikit-learn 
- **Deep Learning Models:** ResNeXt-50 (CNN), LSTM  
- **Dataset:** RSSOD  (Remote Sensing Small Object Detection)  .

---

## 🚀 Future Enhancements  
- Extend to **real-time video stream analysis**  
- Add more object classes for broader applicability  
- Integrate **Explainable AI (XAI)** for better interpretability of predictions  

---

## 📊 Results  

| Metric        | Value   |  
|---------------|---------|  
| Accuracy      | 95%     |  
| Precision     | High    |  
| Recall        | High    |  
| F1-Score      | Balanced|  


---

## 📜 License  
This project is licensed under the MIT License – feel free to use and modify with attribution.  

---

✨ If you found this useful, don’t forget to **⭐ star** the repo and **fork** it!  
