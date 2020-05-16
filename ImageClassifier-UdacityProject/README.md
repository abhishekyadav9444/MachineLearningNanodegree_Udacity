#Image-Classifier

###In this first part of the project, you'll work through a Jupyter notebook to implement an image classifier with PyTorch.
The image classifier to recognize different species of flowers. Dataset contains 102 flower categories.

The project is broken down into multiple steps:

    - Load and preprocess the image dataset
    - Train the image classifier on your dataset
    - Use the trained classifier to predict image content

In Image Classifier Project.ipynb Alexnet from torchvision.models pretrained models was used. It was loaded as a pre-trained network, based on which defined a new, untrained feed-forward network as a classifier, using ReLU activations and dropout. Trained the classifier layers using backpropagation using the pre-trained network to get the features. The loss and accuracy on the validation set were tracked to determine the best hyperparameters.
