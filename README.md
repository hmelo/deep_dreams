# deep_dreams

This directory contains a Jupyter notebook that demonstrates how to generate trippy images using a number of Convolutional Neural Network 
image generation techniques implemented with TensorFlow.

Image(url= "http://my_site.com/my_picture.jpg", width=100, height=100)

- visualizing individual feature channels and their combinations to explore the space of patterns learned by the neural network (see [GoogLeNet](http://storage.googleapis.com/deepdream/visualz/tensorflow_inception/index.html) and [VGG16](http://storage.googleapis.com/deepdream/visualz/vgg16/index.html) galleries)
- embedding TensorBoard graph visualizations into Jupyter notebooks
- producing high-resolution images with tiled computation ([example](http://storage.googleapis.com/deepdream/pilatus_flowers.jpg))
- using Laplacian Pyramid Gradient Normalization to produce smooth and colorful visuals at low cost
- generating DeepDream-like images with TensorFlow

You can view "deepdream.ipynb" directly on GitHub. Note that GitHub Jupyter notebook preview removes 
embedded graph visualizations. You can still see them online 
[using nbviewer](http://nbviewer.jupyter.org/github/tensorflow/tensorflow/blob/master/tensorflow/examples/tutorials/deepdream/deepdream.ipynb)
service.

Make sure you have all the dependencies installed.

To open the notebook, run `ipython notebook` command in this directory, and 
select 'Deep Dream with Inception Network.ipynb' in the opened browser window.
