# Classification of Traffic Signs using Deep Learning

## The Notebook
The python notebook included in this repository uses traffic sign images as traning data (see section "Training Data") to train a neural network to classify these signs. The network saves the configuration with the best performance on the test set and then runs it on 14 external images picked randomly from the internet.

The training data are "boosted" by generating additional sharpened images with affine distortion to emulate different slight change in viewpoint. Data boosting appears to give a 4-5% increase in the test set.    

## The Neural Network
The network employed is a [LeNet](http://yann.lecun.com/exdb/lenet/) variant and the implementation is in [Tensorflow](https://www.tensorflow.org/).   

## Training Data
The training dataset is a subset of the [German traffic sign dataset](http://benchmark.ini.rub.de/?section=gtsdb&subsection=dataset) which can be downloaded [here](https://1drv.ms/u/s!AtmapBHRVgqWgVlGjnDUk8Zn7GZc).


