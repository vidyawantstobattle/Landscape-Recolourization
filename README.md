# Landscape-Recolourization
Train autoencoders on landscape images to colourize black and white landscape images.

Here, I have used keras for building the autoencoder.
I downloaded images from google images using the chrome extension 'Download All Images'. I am including a zipped file of the images. Feel free to add more for training.

rgb2lab conversion of images is done. theory is explained in the notebook 'Image_Recolourization_With_Autoencoders'.


My laptop is a bit of a grandpa, so 20 epochs training took me an hour's time. However, you can see below, the recolourization quality improves with the number of epochs.
If you have the resources or your laptop is not a grandpa like mine, a training of 100 epochs would lead to satisfactory results for you. :) 


Test Image:
![test image](https://github.com/vidyawantstobattle/Landscape-Recolourization/tree/main/test)


After 10 epochs:
![test image](https://github.com/vidyawantstobattle/Landscape-Recolourization/blob/main/results/result(10%20epochs).png)

After 20 epochs:
![test image](https://github.com/vidyawantstobattle/Landscape-Recolourization/blob/main/results/result(20%20epochs).png)

