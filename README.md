# invisible-cloak
I am showing you amazing magic with Computer Vision and ML.
The logic is very simple. I'm extracting each frame of the video, with the help of segmentation.I separate the background and foreground of the image.then I replace the foreground of a particular color with the background which gives the illusion of getting disappeared. I have taken red colored cloth for getting disappeared, you can use any color of your choice.


Workflow of this project will be:

  

1. Importing needed libraries and generate the output video
.CV,numpy,time.

2. Recording and caching the background for each frame.

3. detecting the red portion in each frame

4. Replacing the red portion with a mask image in each frame

5. Producing the surprising output
