# Few-Shot-Learning-for-Multi-Skin-Disease-Detection

This project applies **few-shot learning** techniques to classify skin diseases, specifically **Vitiligo**, **Seborrheic Keratosis**, and **Eczema**, using deep learning models (VGG19, ResNet50, & DenseNet121). The goal of the project is to train models with limited samples and achieve high classification accuracy.

The project focuses on the **3-way N-shot** learning technique, with three different shot configurations (5-shot, 7-shot, and 10-shot), and evaluates the performance of the models using these settings. In the code, we have only shown 3-way 5-shot results, results were obtained for 7-shot and 10-shot by simply changing the parameter values.

## Model Performance

The following are the accuracy results for different models and shot configurations:

### 3-Way 5-Shot:
- **DenseNet121**: Accuracy = **0.9333**
- **ResNet50**: Accuracy = **0.9333**
- **VGG19**: Accuracy = **0.6666**

### 3-Way 7-Shot:
- **DenseNet121**: Accuracy = **0.9523**
- **ResNet50**: Accuracy = **0.9009**
- **VGG19**: Accuracy = **0.7116**

### 3-Way 10-Shot:
- **DenseNet121**: Accuracy = **0.9666**
- **ResNet50**: Accuracy = **0.8333**
- **VGG19**: Accuracy = **0.7366**


