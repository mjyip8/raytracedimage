# raytraced image
CS148 Introduction to Computer Graphics final project.

Code snippets of features I made on top of raytracer. 

#PerspectiveCamera.cpp 
Created a depth of field visual effect by setting the focal distance 8.25 units away. Directed all rays to go through this pinhole location.

#BackwardRenderer.cpp 
Trace function checks whether the ray is in shadow. 

#Raytracer.cpp
Use multithreading to construct different sections of the image and to stitch the parts together. Run the raytracer through 25 iterations and move the camera slightly during each iteration. Then average the colors in each pixel to create the depth of field blurring effect.
