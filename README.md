# Least Squares & Seamless Copy/Paste Documentation

## Background

The primary goal of this assignment is to seamlessly blend an object or texture from a source image into a target image. The insight is that our visual system is often more sensitive to the gradient of an image (how quickly the pixel values change left-right and up-down) than the overall intensity. 

We will therefore set up the problem as finding values for the pasted target pixels that maximally preserve the gradient of the source region without changing any of the background pixels. Note that we are making a deliberate decision here to ignore the overall intensity! So a green hat could turn red, but it will still look like a hat.
