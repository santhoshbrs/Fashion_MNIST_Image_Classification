# Fashion MNIST Image Classification using CNN

dd a logo or relevant image here -->

A Convolutional Neural Network (CNN) based image classification model for the Fashion MNIST dataset. This project aims to accurately classify grayscale images of fashion items into their respective categories.

## Table of Contents


- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Model Architecture](#model-architecture)
- [Results](#results)


## Dataset

The Fashion MNIST dataset consists of 60,000 training images and 10,000 testing images, categorized into 10 classes:
- 0: T-shirt/top
- 1: Trouser
- 2: Pullover
- 3: Dress
- 4: Coat
- 5: Sandal
- 6: Shirt
- 7: Sneaker
- 8: Bag
- 9: Ankle boot


## Dependencies

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib


## Model Architecture

The CNN model architecture used in this project consists of multiple convolutional layers followed by max-pooling layers, dropout for regularization, and fully connected layers for classification. You can find the details of the model architecture in the `model.py` file.

## Results

After training the model, you can expect to see the accuracy and loss metrics printed in the console. Additionally, the `evaluate.py` script provides a detailed evaluation of the model's performance on the test set.



Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
