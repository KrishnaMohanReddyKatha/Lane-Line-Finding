PipeLine:
* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Detect lane pixels and fit to find the lane boundary.
* Determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

Future Scope:
This model might fail in the case where the lane line is completely covered by a shadow or if too much noise exits. To make it more robust we need to use the info about lanes detected in the previous frames to detect in the current frame. This approach would make the model more robust and also increases the speed of detection considerably.

Final image, video of lane detection are in the repository.
