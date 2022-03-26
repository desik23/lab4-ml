# lab4-ml

## 1 Deep Learning with R / Python Exercises
You’ll first learn about Computer Vision techniques by going through the Chapter 5 lab exercises:

5.1 Introduction to convnets R: html, Rmd ; Python: html, ipynb

5.2 Training a convnet from scratch on a small dataset R: html, Rmd ; Python: html, ipynb

The subsequent lab exercises meet the limits of using a CPU over a GPU, which is not available on taylor.bren.ucsb.edu. Here’s as far as I was able to get for demonstration sake, but you’re not expected to run this. You might want to try if you have personal computer with a GPU setup.

5.3 Using a pretrained convnet R: html, Rmd ; Python: html, ipynb

## 2 iNaturalist
The main lab that you’ll turn in is to apply these techniques to a small subset of the iNaturalist species imagery. These data were downloaded from the links provided at github.com/visipedia/inat_comp:2021/. Of all the 10,000 species and many images for each from training (Train), training mini (Train Mini), validation (Val) and test images, you’ll draw only from the Train Mini set of images:



The first step is to move the images into directories for the variety of models. 

Your task is to apply your deep learning skills to build the following models:

2 Species (binary classification) - neural net. Draw from 3.4 🍿 Movies (binary classification). You’ll need to pre-process the images to be a consistent shape first though – see 5.2.4 Data preprocessing.

2 Species (binary classification) - convolutional neural net. Draw from the dogs vs cats example.

10 Species (multi-class classification) - neural net. Draw from 3.5 📰 Newswires (multi-class classification).

10 Species (multi-class classification) - convolutional neural net. Draw from dogs vs cats example and update necessary values to go from binary to mult-class classification.

In your models, be sure to include the following:

-Split the original images per species (n=50) into train (n=30), validate (n=10) and test (n=10). These are almost absurdly few files to feed into these complex deep learning models but will serve as a good learning example.

-Include accuracy metric and validation in the fitting process and history plot.

-Evaluate loss and accuracy on your test model results. Compare standard neural network and convolutional neural network results.
