# Smile-Detection-using-CNN
Face detection in cameras, especially the 'smile' to automatically capture photos was implemented in digital cameras since the early 2000s. Due to the advancements in machine learning, we are now able not just to recognize smiles, but various other expressions to initiate multiple functions in our systems. The project is an exploration detailing the mechanisms used specifically to detect smiles.
## Project Description
Due to the 2-dimensionality of images, it will be humongous to feed each pixel to an input in the training of models. Hence, the principle of convolution is employed to construct a Convoluted Neural Network (CNN) that after reducing the input parameters of an image, it is passed through a fully connected neural network.

The main stages of the algorithm is as follows:
1. Pre-process the image to a standard size and color scaling.
2. Train the CNN over the dataset.
3. Predict the label for the required test set.

The basic layer structure used to construct the CNN is as follows:
1. Convolution-1 (2D)            _the input size equal to the pixel dimensions of the image_
2. Max Pooling-1 (2D)
3. Convolution-2 (2D)
4. Max Pooling-2 (2D)
5. Fully Connected-1 (Linear)
6. Fully Connected-2 (Linear)
7. Fully Connected-3 (Linear)    _no. of neurons equal to the number of label classes_
## Dataset
This project uses the SMILEs data set from Hromada found [here](https://github.com/hromi/SMILEsmileD.git)
## How to RUN
1. Download the dataset and the jupyter notebook locally.
2. Update the path to a dataset in the notebook.
3. Run through the cells in the notebook in order if you want to train the neural network.
4. If only prediction is needed, create a folder with test images tightly cropped to the face (square ratio) and update the path.
5. Run to get the prediction.
## Credits
The Deep Learning With PyTorch playlist on YouTube by John Elder (Codemy.com) provided the necessary knowledge for implementation of the CNN. And Hromada for the extensive labeled dataset. 
