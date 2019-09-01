# deep-learning-testbed

Code for doing deep learning, mostly on medical images (in python) 

## Install Anaconda (I use 4.7.11)
I use the latest 3.7 Linux version from https://www.anaconda.com/distribution/#download-section.

## Install TensorFlow 1.9 (CPU)
* (conda env list)
* (conda env remove -n tensorflow_cpu)
* conda update conda
* conda create -n tensorflow_cpu pip python=3.6
* conda activate tensorflow_cpu
* (conda deactivate)
* pip install --ignore-installed --upgrade tensorflow==1.9

### Test
* python
* import tensorflow as tf
* hello = tf.constant("hello TensorFlow!")
* sess=tf.Session() 
* print(sess.run(hello))

## Install Keras
* pip install keras
* pip install h5py
* pip install graphviz
* pip install pydot

### Tests
https://keras.io/examples/mnist_cnn/
