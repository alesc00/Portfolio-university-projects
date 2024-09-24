# 🚦 Deep Learning Traffic Sign Recognition

This project develops a Convolutional Neural Network (CNN) to classify traffic signs from images. The dataset consists of 741 images containing road scenes with multiple traffic signs, categorized into four classes: Prohibitory, Danger, Mandatory, and Other. 

## 📁 Project Contents

- **traffic sign recognition.ipynb**: Jupyter Notebook containing the full implementation of the CNN model for traffic sign classification.
- **data/**: Due to the size of the dataset, it is not included here, but you can find instructions in the notebook on how to download it.

## 📊 Summary

### Dataset:
- **741 images**: Each image may contain multiple traffic signs.
- **4 classes**: Prohibitory, Danger, Mandatory, and Other.

### Goal:
To build a CNN capable of accurately classifying road signs in images. CNNs are particularly effective for image classification tasks as they use convolutional filters to learn and identify visual patterns like edges, shapes, and textures.

### 📈 Key Analyses:
- **Data Loading and Preprocessing**: Use of PyTorch for loading and transforming the images for training the CNN.
- **Model Building**: The CNN is designed and implemented using PyTorch, leveraging its flexibility and dynamic graph capabilities.
- **Training and Evaluation**: The model is trained to classify images into one of the four traffic sign categories. Model performance is evaluated on a test set.

## 🛠️ Libraries Used:
- **PyTorch**: For building and training the CNN model.
- **torchvision**: For handling image transformations and dataset operations.
- **matplotlib**: For visualizing the training process and model performance.
- **numpy**: For data manipulation.

## 📌 Conclusions:
This project showcases how CNNs can be effectively used for image classification tasks. The model was trained to classify traffic signs, with the potential for further improvements in performance by tuning hyperparameters or increasing the dataset size.

⚠️ **Note**: The dataset is not included in this repository due to its size. Refer to the notebook for instructions on how to download and prepare the data.

