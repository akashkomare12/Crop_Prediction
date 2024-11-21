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

### **Classes**
The dataset includes the following crop types:
1. Wheat  
2. Rice  
3. Sugarcane  
4. Maize  
5. Jute  

## Methodology
1. **Data Augmentation**:
   - Techniques: Horizontal flip, rotation, horizontal and vertical shifts.
2. **Model Training**:
   - The model was trained on the augmented dataset and saved as a `.h5` file.
3. **Evaluation**:
   - Tested using the provided test dataset to validate performance.

## Acknowledgments
- Special thanks to Kaggle for providing the dataset and the platform to host the project.  
- Dataset Link: [Agriculture Crop Images](https://www.kaggle.com/datasets/aman2000jaiswal/agriculture-crop-images)  
- Code Link: [Crop Prediction Notebook](https://www.kaggle.com/code/akashkomare/crop-prediction/edit)

---

**If you find this project helpful, don't forget to upvote and star the repository!**
``` 

Let me know if you need further refinements or help in structuring your GitHub repository!
