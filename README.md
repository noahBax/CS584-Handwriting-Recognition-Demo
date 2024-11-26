# CS 584 Project Repository

**"*Nearly* Outstanding Character Recognition Algorithm"**
or **NOCRA** for short.

Our group decided to focus on recognizing hand-written characters. We trained
our model using images from EMNIST which is a variant of the MNIST database.
EMNIST is a collection of 810,000 28x28 images. For our purposes, we used
*By_Merge* hierarchy which combines some of the labels because they are similar to
each other. For example, 'C' and 'c' are combined to be just 'c'.

Our model is a CNN with a feature extraction stage consisting of 2
Convolution-ReLU-Pooling sequences and a classification stage consisting of 1
dense layer fully connect to a dense output layer.

The libraries you will need to interactively train the model and run the demo
script are
- ipykernel
- NumPy
- TensorFlow
- Matplotlib

and the versions we compiled the model with  have been included in the
requirements.txt. To install them run
```
pip install -r requirements.txt
```

## Sources
G. Cohen, S. Afshar, J. Tapson and A. van Schaik, "EMNIST: Extending MNIST to
handwritten letters," 2017 International Joint Conference on Neural Networks
(IJCNN), Anchorage, AK, USA, 2017, pp. 2921-2926, doi:
10.1109/IJCNN.2017.7966217.