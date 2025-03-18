# CNN2RF-ImageClassifier


## Project Overview

In this project, I worked with the **Fashion MNIST dataset**, designing a **Convolutional Neural Network (CNN)** architecture for image classification. The goal was to build a model capable of classifying images of fashion items into one of 10 categories.

### Key Steps and Approaches:
- **CNN Architecture**: Designed and implemented a CNN model to extract meaningful features from the input fashion item images.
- **Feature Extraction**: The CNN acts as a **feature extractor**, learning discriminative features from the images through its convolutional layers.
- **Random Forest Classifier**: The extracted features are then passed to a **Random Forest classifier**, which makes the final classification decision.
- **Hyperparameter Tuning**: Used **RandomizedSearchCV()** to find the optimal hyperparameters for the **Random Forest** algorithm, enhancing its performance.
- **Fashion Recommendation Systems**: Improved fashion recommendation systems by providing accurate item classification and personalized suggestions.

## Files in the Project

1. **Image_Classifier.ipynb**: The Jupyter Notebook where the CNN architecture and classification using Random Forest are implemented.
2. **Image_Classifier.pdf**: A detailed report that explains the working and methodology of the image classification model.

## Conclusion

The model successfully classifies fashion items into different categories. The CNN extracts features, which are then passed on to the Random Forest classifier for making final classification decisions. This approach enhances the performance of fashion recommendation systems, providing more accurate suggestions and classifications.
