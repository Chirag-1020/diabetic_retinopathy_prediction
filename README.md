# diabetic_retinopathy_prediction
#  Diabetic Retinopathy Prediction 

This project uses deep learning to detect **diabetic retinopathy** (DR) from retinal fundus images. It is designed to assist in early diagnosis and reduce the risk of vision loss in diabetic patients.

---

##  Table of Contents

- [Overview](#-overview)
- [Dataset](#-dataset)
- [Model](#-model)
- [Installation](#-installation)




##  Overview

Diabetic Retinopathy is a leading cause of blindness. This project uses a convolutional neural network (CNN) to classify retinal images into five DR stages:

- 0: No DR  
- 1: Mild  
- 2: Moderate  
- 3: Severe  
- 4: Proliferative DR  

---

## 📁 Dataset

- Source: [Kaggle Diabetic Retinopathy Detection](https://www.kaggle.com/competitions/aptos2019-blindness-detection)
- Images: Retinal fundus photographs
- Labels: DR severity level (0–4)

> **Note**: Dataset not included due to size. Please download it manually from Kaggle.

---

## Model

- Framework:  TensorFlow
- Architecture: Transfer Learning with  EfficientNet
- Loss: CrossEntropy
- Optimizer: Adam
- Input size: 224×224 

---

## Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/Chirag-1020/diabetic_retinopathy_predictionn.git
   cd diabetic_retinopathy_prediction
