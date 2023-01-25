# Pan-Card-tampering-Detection

The purpose of this project is to detect pan card tampering using Computer vision. 
This project will help the organization in detecting whether the Id i.e. 
the PAN card provided to them by their employees or customer or anyone is original or not.

*#STEPS *

Get Images from User
Check for size and Format of the Image
Change shape and size of the image according to the original image
Convert the image to grayscale
Find the similarity index of the images
Finding the threshold of the image
Finding the contour and grab those contours using Imutils
Draw Bounding Rectangle using these contours
Plot difference, threshold, original and tempered image
Compare all the images and check the similarity score to decide tampering.
