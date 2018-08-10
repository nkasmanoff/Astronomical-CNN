Contained wihtin this repository is the type of image analysis I imagine will be used for the Large Synoptic Survey Telescope (LSST). While I have no affiliation to the project, I am deeply interested in the possibilities of applied machine learning to astronomy. 

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



Potential Issues
----------------


How to get a training dataset! 

Can't just google image star, will get a bunch of different things, only want the bright circle
