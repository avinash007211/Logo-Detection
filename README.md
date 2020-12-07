# Logo-Detection

  

The logo detection works on the object detection API from Google Tensor Flow

Making a machine learning model from scratch needs a lot of time and skills, so transfer learning helps you to make the model detect and identify images based on your own data set. We train an existing machine learning model for that we have two ways to achieve what we desire:
•	The last layer only retraining: In last layer retraining only, the last layer is retrained where the end classification occurs, it is best to use for a tiny data set.
•	Full model retraining: In full model retraining the whole model is retrained, here each and every neural network layer is retrained. It is more accurate and time consuming as per compared to last layer retraining.
To start Transfer learning, we need to do it in a virtual environment or a virtual container like docker. Here Docker is used as it isolates packages like TensorFlow, python, pre-training scripts, NumPy array and much more, the installation and steps to be followed for Docker installation is given here https://docs.docker.com/engine/install/ubuntu/. 

More info can be found here for training on own dataset https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2.md
