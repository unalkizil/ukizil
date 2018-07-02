# Machine Learning Example
## Image Classification
A sample program by which user can classify among set of images.  
We are retraining final layer of images to create labels and graphs for our provided set of images, classification model is getting created by Transfer Learning.  
  
In this exercise, we will retrain a MobileNet. MobileNet is a a small efficient convolutional neural network
## 

![alt text](https://drive.google.com/uc?id=1zcscLsVLss_ponH3HEGRl2igVX2qwHus)
## 
We are using TensorFLow library of python here. TensorFlow is an open-source software library for dataflow programming across a range of tasks. It is a symbolic library used for machine learning applications such as neural networks.
  
Prerequisites is to install TensorFlow:  
> `$ pip install --upgrade "tensorflow==1.7.*"`  


Training progress can be monitored by launching tensorboard in background  
> `$ tensorboard --logdir tf_files/training_summaries &`

Stop tensorboard server  
>`$ pkill -f "tensorboard"`

##
##### Complete code image: `$ docker pull tarunmaini/image-classifier`
> **https://hub.docker.com/r/tarunmaini/image-classifier**

