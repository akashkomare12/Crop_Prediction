# Crop Prediction using CNN

## About the Project

This project uses Convolutional Neural Networks (CNN) to classify images of agricultural crops into 5 different classes: Maize, Wheat, Jute, Rice, and Sugarcane. The model was trained using a crop image dataset that includes images captured from different angles, including aerial and ground views, and in various life cycle stages of each crop.

The project leverages TensorFlow's Keras API for building and training the model, and OpenCV for image preprocessing. The final model is saved in the `.h5` format and used for making predictions on new crop images.

## Dataset

The dataset consists of multiple images for each of the five crops:
- **Maize**
- **Wheat**
- **Jute**
- **Rice**
- **Sugarcane**

### Context

- The dataset contains **40+ images** of each crop type.
- **Dataset (kag2)** contains **159+ augmented images** for each crop, with augmentations such as horizontal flips, rotations, and shifts (both horizontal and vertical).
- The dataset includes various images capturing the crops from aerial to ground views and in different stages of growth.

**Test Data:**  
Test data can be found at the following Kaggle link:  
[**Crop Test Data**](https://www.kaggle.com/aman2000jaiswal/testssss)  
Or, you can use the newly uploaded version of the dataset: `test_crop_images`.

You can also download the `Crop_details.csv` file that contains all images and their labels.

### Task

The objective of this project is to classify crop images into five categories: **Maize, Wheat, Jute, Rice,** and **Sugarcane**. The goal is to achieve high accuracy in classifying the images, leveraging image augmentation and deep learning.

## Project Structure

This repository includes the following files:

1. **`cropprediction.h5`** - The trained model saved in `.h5` format, which can be used to predict crop types from input images.
2. **`cropprediction.ipynb`** - The Jupyter Notebook used for training the model, evaluating the performance, and running predictions.

## use both the files for predicting the crop

### Training the Model

The model was trained using the following steps:
1. **Data Augmentation:** The training data was augmented using horizontal flips, rotations, and shifts to improve the generalization of the model.
2. **Model Architecture:** A Convolutional Neural Network (CNN) was used with several convolutional and pooling layers followed by dense layers.
3. **Optimization:** The model was trained with an Adam optimizer, using categorical cross-entropy as the loss function for multi-class classification.

## Dataset Source

- **Kaggle Dataset:**  
  The dataset used for training can be found on Kaggle:  
  [**Crop Dataset**](https://www.kaggle.com/aman2000jaiswal/testssss)

- You can download the `test_crop_images` dataset for testing and make predictions on the images included in that set.

## Kaggle Code

You can view the Kaggle code used for training the model here:  
[**Kaggle Code**](https://www.kaggle.com/aman2000jaiswal/crop-prediction)

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Contributions are welcome, especially for improving the model's accuracy or adding more crop categories.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

This `README.md` contains all necessary information for setting up, using, and understanding your crop prediction project, along with the relevant links to the Kaggle dataset and code. Let me know if you'd like any adjustments!
