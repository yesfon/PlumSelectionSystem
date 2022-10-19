# Requirements

# PlumSelectionSystem
This repository is made up of two main elements, the first is a data set that is made up of images taken from post-harvest samples of the fruit known as plum, specifically of the horvin variety.
The description of the data set is as follows:

- First class plums: 606 samples
- Second class plums: 705 samples
- Third class plums: 557 samples

The second element is composed of two codes made in jupyter notebook. The first `CNN_MULTI.ipynb` is the training of a convolutional neural network that allowed to solve the classification of plums in three different categories. The code shows the metrics obtained in training and validation, where around 92% accuracy is obtained for the validation set. Also, the model that was saved after training the algorithm is available in the `CNN_Plum.h5` file, which can be loaded with the _Keras_ library. The second code takes the trained model and extracts the information learned by the network in its filters after it had been trained, in addition, the GradCam algorithm is applied to identify which sections of the images that enter the algorithm, CNN will pay special attention, the above is available in the `Filters.ipynb` notebook.

The idea of this proposal was to generate a compact and low-cost solution that was based on artificial intelligence techniques. In order to present a complete solution to the problem, a conveyor belt prototype is designed that allows carrying out the classification of this fruit beyond the simulation, that is, making a tangible classification of the fruits. The following link shows how the prototype works:

- https://youtu.be/xAGpDa8FeNA
