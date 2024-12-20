This project demonstrates how to train an image classifier from scratch using TensorFlow and Keras. The model is trained on the Kaggle Cats vs Dogs dataset to classify images as either a cat or a dog.

## Description

This Colab notebook provides a step-by-step guide to building and training an image classification model. It covers the following:

1. Setting up the data directory and downloading the dataset.
2. Installing the required libraries.
3. Reading and analyzing the data.
4. Building a basic CNN model.
5. Training and evaluating the model.
6. Making predictions on new images.
7. Visualizing the kernel feature maps.

## Dataset

The Kaggle Cats vs Dogs dataset is used for this project. You can find the dataset here:

[https://www.kaggle.com/datasets/salader/dogs-vs-cats?select=train](https://www.kaggle.com/datasets/salader/dogs-vs-cats?select=train)

## Results

The trained model achieves an accuracy of approximately 92% on the test set. The notebook also includes visualizations of the model's performance and the kernel feature maps.

## Next Steps

- Experiment with data augmentation to improve model generalization.
- Adjust the model architecture to potentially increase accuracy.
- Explore hyperparameter tuning for optimal performance.
- Consider transfer learning for faster training and better results.
- Implement model saving and deployment for real-world applications.

## References

- [ImageDataGenerator](https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator)
- [image_dataset_from_directory](https://www.tensorflow.org/api_docs/python/tf/keras/utils/image_dataset_from_directory)
- [Calculating output sizes after a convolution layer](https://stackoverflow.com/questions/56450969/how-to-calculate-output-sizes-after-a-convolution-layer-in-a-configuration-file)
- [Keras Model](https://www.tensorflow.org/api_docs/python/tf/keras/Model)
