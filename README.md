FIX https://github.com/arahusky/Tensorflow-Segmentation
can't use when commit 7aabc69a07eb9895e8eb92f21dcb91c6a1139b27,
fix module name can't find, tensorflow api too old......
# Project overview

The main file of the project is *convolutional_autoencoder.py*, which contains code for dataset processing (class Dataset), model definition (class Model) and also code for training. 

To abstract layers in the model, we created *layer.py* class interface. This class has currently two implementations: *conv2d.py* and *max_pool_2d.py*.

To infer on the trained model, have a look at *infer.py* file.

# Requirements:
- Python 3.5
- Tensorflow > 1.0
- Opencv 3.x
- imgaug

