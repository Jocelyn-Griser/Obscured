# Obscured
Mask images from unwanted AI models


This program takes an image and creates a series of overlays so that unwanted AI models will be unable to replicate the image.
It uses the Sobel, ORB, and Canny algorithms to create these overlays, with the goal that image will appear unchanged to the human eye.

There are (at the moment) 16 parameters the user can change, and the output will include image showing every step of the process to help you modify the parameters to your choosing.

You can run this in the provided colab notebook or from https://huggingface.co/spaces/JocelynG/Obscured
