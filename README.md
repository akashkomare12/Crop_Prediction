# Crop Prediction Using Agriculture Crop Images

## Overview
This project aims to classify five types of agricultural crops (wheat, rice, sugarcane, maize, and jute) based on their images. The dataset contains various images of crops in different stages of their lifecycle, captured from aerial and ground views. Advanced data augmentation techniques are employed to enhance model performance and improve classification accuracy.

## Dataset
The dataset used for training and evaluation is sourced from Kaggle:  
[**Agriculture Crop Images Dataset**](https://www.kaggle.com/datasets/aman2000jaiswal/agriculture-crop-images)

### **Dataset Details**
- **Crop Images Dataset**: Contains 40+ images per crop type.
- **Augmented Dataset (kag2)**: Contains 159+ augmented images per crop type.
  - Augmentation techniques: Horizontal flip, rotation, horizontal shift, vertical shift.
- **Crop_details.csv**: Includes image paths and corresponding labels.
- **Test Data**: Found [here](https://www.kaggle.com/aman2000jaiswal/testssss) or in the updated version as `test_crop_images`.

### **Classes**
The dataset includes the following crop types:
1. Wheat  
2. Rice  
3. Sugarcane  
4. Maize  
5. Jute  

## Task
The primary objective is to develop a model that classifies crop images into one of the five categories with high accuracy. Predictions can be submitted on `testdata.csv`, available [here](https://www.kaggle.com/aman2000jaiswal/testssss).

## Methodology
1. **Data Augmentation**:
   - Techniques: Horizontal flip, rotation, horizontal and vertical shifts.
2. **Model Training**:
   - The model was trained on the augmented dataset and saved as a `.h5` file.
3. **Evaluation**:
   - Tested using the provided test dataset to validate performance.

## Instructions to Run the Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/username/crop-prediction.git
   cd crop-prediction
