UPDATE 8/8
===========

Today I successfully was able to pull images of galaxies from the web and plug them into a weak, but good enough, CNN classifier in order to distinguish a galaxy from a ... dog. This proved effective and I confirmed I had the abilities to plug in the correct image shape, currently working within the realms of RGB imaging but that may end up changing. 

Next up will be working with large images, isolating the unique sources on each, and then identifying from there. For such a task it seems necessary to use RGB since color definitely plays a role especially in this noisier data to distinguish different sources. 

Good start!



I've now created the abilitiy to isolate each object in the example LSST image, meaning I will have a large number of inputs to identify with this CNN. 

The CNN is not able to perform accurately however, and I am working on this. 


I am now studying how the CIFAR 10 Dataset works, and it is clear that I need FAR more practice and testing data to create a capable CNN. So I am going to look at the CNN siraj mentions as already being functional, and see how it handles the task I'm asking about. 




Contained wihtin this repository is the type of image analysis I imagine will be contained/useful for the Large Synoptic Survey Telescope (LSST). While I have no affiliation to the project, I am deeply interested in the possibilities of applied machine learning to astronomy. 

For a project like the LSST where the amount of data is far beyond human processing, applied machine learning will prove to be a valuable tool for accelerating the consumption of data and results. 


For starters I have downloaded an image from the web designed to appear like an example image (https://www.lsst.org/?q=node/75) taken by the LSST, and will demonstrate how ML can be used to quickly characterize characteristics such as the presence of stars, galaxies, etc. etc. 



METHODOLOGY
-----------


I will be training a convolutional neural network based on google search results for the following astronomical objects, star, galaxy, etc. and then isolate each of these unique bodies contained within the image based on the brightness signature 


1. Identify bright spots

2. Resize images based on this

3. Plug into CNN, and output the most likely identification

4. Count up # of objects, and positions. 

And this can then be applied to all sorts of images!



Potential Issues
----------------


How to get a training dataset! 

Can't just google image star, will get a bunch of different things, only want the bright circle

galaxy seems fairly possible


Getting the computing space for this... 


Notes

Using that fatkun thing for downloading batch images for training 


Will be using the Deep learning w keras notebook to help build baseline model CNN

Will be using some new form of image resizing I have yet to create in order to identify the bright pixels, and fixed radius / image size. Should cover all of them, placing in center the image of interest. 
