# deep_dreams

This directory contains Jupyter notebook that demonstrates a number of Convolutional Neural Network image generation techniques implemented with TensorFlow:

visualizing individual feature channels and their combinations to explore the space of patterns learned by the neural network (see GoogLeNet and VGG16 galleries)
embedding TensorBoard graph visualizations into Jupyter notebooks
producing high-resolution images with tiled computation (example)
using Laplacian Pyramid Gradient Normalization to produce smooth and colorful visuals at low cost
generating DeepDream-like images with TensorFlow
You can view "deepdream.ipynb" directly on GitHub. Note that GitHub Jupyter notebook preview removes embedded graph visualizations. You can still see them online using nbviewer service.

In order to run the notebook locally, the following dependencies must be installed:

Python 2.7 or 3.5
TensorFlow (>=r0.7)
NumPy
Jupyter Notebook
To open the notebook, run ipython notebook command in this directory, and select 'deepdream.ipynb' in the opened browser window.
