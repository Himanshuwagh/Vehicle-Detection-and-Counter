# Vehicle Detection and Counter

This sample project focuses on "Vechicle Detection, Tracking and Counting" using basic Opencv principles. 

![Alt Text](https://user-images.githubusercontent.com/22610163/30249200-efa2b594-963f-11e7-8c3e-b378cbf49101.gif)

The developing is on progress! This sample project will be updated soon, the more accurated project using tensorflow will be updated soon in this repo!

### General Capabilities of This Sample Project
This sample project has more than just counting vehicles, here are the additional capabilities of it:

- Detection of the vehicles.
- Prediction of approximate vehicle size

### Frame Differencing
A video is a set of frames stacked together in the right sequence. So, when we see an object moving in a video, it means that the object is at a different location at every consecutive frame.

### Finding Contours
The contours are used to identify the shape of an area in the image having the same color or intensity. Contours are like boundaries around regions of interest. So, if we apply contours on the image after the thresholding step, we would get the result

The white regions have been surrounded by grayish boundaries which are nothing but contours. We can easily get the coordinates of these contours. This means we can get the locations of the highlighted regions.






