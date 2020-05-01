# INFO7390-Prediction_of_Image_using_CNN
Required libraries:
Install Keras from PyPI (recommended):
Note: These installation steps assume that you are on a Linux or Mac environment. If you are on Windows, you will need to remove sudo to run the commands below.
sudo pip install keras
If you are using a virtualenv, you may want to avoid using sudo:
pip install keras
Alternatively: install Keras from the GitHub source:
First, clone Keras using git:
git clone https://github.com/keras-team/keras.git
Then, cd to the Keras folder and run the install command:
cd keras
sudo python setup.py install
Install Tensorflow
To install the current release, which includes support for CUDA-enabled GPU cards (Ubuntu and Windows):
$ pip install tensorflow
A smaller CPU-only package is also available:
$ pip install tensorflow-cpu
To update TensorFlow to the latest version, add --upgrade flag to the above commands.

# Project Workflow

- Import the required Python libaries at one place
- Read the train and test data set
- Display images from test and train dataset.
- Create CNN models. 
- Evaluate the model based on accuracy of training set and accuracy of validation set.
- Hyper Parameters Tuning for the model for params:
    1.  Changed Activation function in base model. 
    2.  Changed Cost function in base model.
    3.  Changed no. of epochs in base model.
    4.  Changed optimizer in base model.
    5.  Changed no. of convolution layers in base model.
    6.  Changed initilization parameter in base model.
- Predict the class of image using different model.