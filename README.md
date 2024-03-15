# Smile-Detection-using-CNN
Face detection in cameras, especially the 'smile' to automatically capture photos was implemented in digital cameras since the early 2000s. Due to the advancements in machine learning, we are now able not just to recognize smiles, but various other expressions to initiate multiple functions in our systems. The project is an exploration detailing the mechanisms used specifically to detect smiles.
## Project Description
Due to the 2-dimensionality of images, it will be humongous to feed each pixel to an input in the training of models. Hence, the principle of convolution is employed to construct a Convoluted Neural Network (CNN) that after reducing the input parameters of an image, it is passed through a fully connected neural network.

The main stages of the algorithm is as follows:
1. Pre-process the image to a standard size and color scaling.
2. Train the CNN over the dataset.
3. Predict the label for the required test set.

The basic layer structure used to construct the CNN is as follows:
1. Convolution-1 (2D)    _with the input size equal to the dimensions of the image
2. Max Pooling-1 (2D)_
3. Convolution-2 (2D)
4. Max Pooling-2 (2D)
5. Fully Connected-1 (Linear)
6. Fully Connected-2 (Linear)
7. Fully Connected-3 (Linear)
