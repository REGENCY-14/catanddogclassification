# Cat vs. Dog Image Classification using CNN
This project employs a Convolutional Neural Network (CNN) to classify images of cats and dogs. The model is trained on labeled datasets to predict whether an input image contains a cat or a dog.

## Key Features
- Utilizes a deep learning-based CNN for accurate image classification.
- Processes cat and dog images for binary categorization.
- Provides comprehensive performance evaluation using Confusion Matrix, ROC Curve, and Precision-Recall curves.

## Dataset
The project uses datasets containing labeled images of cats and dogs. Suggested datasets include:
- [Kaggle Cats vs. Dogs Dataset](https://www.kaggle.com/c/dogs-vs-cats/data)

### Directory Structure
Since the complete dataset contains 25,000 images, they are not included in the repository. After downloading the dataset from Kaggle, organize the files as follows:

```
| Cats-and-Dogs-Classification-using-CNN
|
| database
|        | 
|        | train
|        |     |
|        |     | dogs
|        |     |    |
|        |     |    |dog.1.jpg
|        |     | 
|        |     | cats
|        |     |    |
|        |     |    |cat.1.jpg
|        |
|        | test
|        |     |
|        |     | dogs
|        |     |    |
|        |     |    |dog.1.jpg
|        |     | 
|        |     | cats
|        |     |    |
|        |     |    |cat.1.jpg
```

## Model Architecture
The CNN model is composed of the following key layers:
1. **Convolutional Layers:** Extracts features from the input images.
2. **Pooling Layers:** Reduces spatial dimensions while retaining essential features.
3. **Fully Connected Layers:** Maps features to the output categories.
4. **Output Layer:** Uses a softmax or sigmoid activation for binary classification.

## Performance and Results
- The model achieves approximately 95% accuracy in classifying cat and dog images.
- Performance evaluation includes key metrics such as Confusion Matrix, Precision, and Recall.
