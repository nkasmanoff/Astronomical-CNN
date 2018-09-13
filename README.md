Contained within this repository is the type of image analysis I imagine will be used for the Large Synoptic Survey Telescope (LSST). While I have no affiliation to the project, I am deeply interested in the possibilities of applied machine learning to astronomy. 

For a project like the LSST where the amount of data is far beyond human processing, applied machine learning will prove to be a valuable tool for accelerating the consumption of data and results. 


For starters I have downloaded an image from the web designed to appear like an example image (https://www.lsst.org/?q=node/75) taken by the LSST, and will demonstrate how ML and data preprocessing can be used to quickly characterize the number of stars, galaxies, asteroids, etc. that may be present in such a survey image.  



METHODOLOGY
-----------


I will be training a convolutional neural network based on google search results for the following astronomical objects, star, galaxy, etc. and then isolate each of these unique bodies contained within the image based on the brightness signature 


1. Identify bright spots

2. Resize images based on this

3. Count up # of objects, and positions. 

4- Play around with different python packages and ML tools, and see if I can correctly distinguish different objects in this example image. 
And this can then be applied to all sorts of images!
