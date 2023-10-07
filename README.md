# Handwritten_digit_recognition
# Introduction
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms.

In this notebook we will classify handwritten digits using a simple neural network which has only input and output layers. We will than add a hidden layer and see how the performance of the model improves.

Our goal is to correctly identify digits from a dataset of tens of thousands of handwritten images.

# Result

Model generally perform better when trained on augmented data as compared to normal data

The CNN model have higher validation accuracy on augmented data than on normal data.
The CNN model has the lowest loss, lowest validation loss.
CNN is the best performing model whereas KNN is least performing model on this dataset.
Based on the provided data, it appears that the CNN model trained on augmented data has the highest validation accuracy among the three models evaluated, with a accuracy of 99%. Whereas KNN,SVM having accuracy of 96% and 97%.
