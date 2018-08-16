Contained within this repository is the type of image analysis I imagine will be used for the Large Synoptic Survey Telescope (LSST). While I have no affiliation to the project, I am deeply interested in the possibilities of applied machine learning to astronomy. 

For a project like the LSST where the amount of data is far beyond human processing, applied machine learning will prove to be a valuable tool for accelerating the consumption of data and results. 


For starters I have downloaded an image from the web designed to appear like an example image (https://www.lsst.org/?q=node/75) taken by the LSST, and will demonstrate how ML can be used to quickly characterize characteristics such as the presence of stars, galaxies, etc. 



METHODOLOGY
-----------


I will be training a convolutional neural network based on google search results for the following astronomical objects, star, galaxy, etc. and then isolate each of these unique bodies contained within the image based on the brightness signature 


1. Identify bright spots

2. Resize images based on this

3. Plug into CNN, and output the most likely identification

4. Count up # of objects, and positions. 

And this can then be applied to all sorts of images!



Update 8/16
-----------

I've moved the neural network to google colab, where I have free access to a gpu to accelerate the training and testing time. The next step is figuring out how to upload data to it! 

For getting a training dataset of galaxies, the best resource I've found so far is using the Kaggle Galaxy Zoo Classification Challenge. The training dataset contains >60000 images of galaxies with all kinds of morphologies, so for the purposes of this project this seems sufficent.  

I also need to determine a proper threshold for the example picture, and what I want to deem a fragment of the image worth categorizing. 

Another important task is the image resizing/reshaping to optimize the CNN. Still thinking this one over... 
