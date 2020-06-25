# Hand-recognition
The project is to find hand in specific to find the no.of.fingers shown in the screen and its corresponding gesture.
Step that is taken placed in this project :

1) Capture frame and convert into grayscale.

2) Blur the image. Bluring is done using Gaussian bluring.

3) Next step is apply threshold on it. This is done using opencv. Using opencv we can able calculate the threshold from the histogram of the captured image.

4) Then we have to draw the contours(ie. to find finger,hand-Region of interest).

5) The image will be with some deviation so we have to apply convex hull and the find the tip of finger. Even this has some deviation to avoid this we use convexity defect which finds the deepest point of deviation on the hull points.

6) The final step to identify the gesture is to compare the captured image with the register gestured.

 
