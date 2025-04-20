# Vehicle Image Classification using CNN

This project is a deep learning-based image classification model built using TensorFlow and Keras. The model classifies vehicle images into five categories: **Car, Bus, Truck, Motorcycle, and Airplane**.

---

## Dataset

The dataset was self-curated by web scraping 1,000 images per class:
- Car
- Bus
- Truck
- Motorcycle
- Airplane

Each image was resized and normalized before training.

---

## Model Architecture

The Convolutional Neural Network (CNN) was built with the following components:
- **Batch Normalization**
- **Dropout for regularization**
- **Early Stopping to prevent overfitting**
- **Softmax activation for multi-class classification**

Training and evaluation were done on an 80-20 train-test split.

---

## Performance

- **Accuracy:** 80% on the test set  
- **Loss Function:** Categorical Crossentropy  
- **Optimizer:** Adam  

---

## Future Improvements

- Add data augmentation to increase robustness
- Try transfer learning with MobileNetV2 or EfficientNet
- Deploy the model using Streamlit or Flask

