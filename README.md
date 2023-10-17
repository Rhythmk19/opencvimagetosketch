# opencvimagetosketch
**IMAGE TO PENCIL SKETCH WITH PYTHON :-**

**1.** Read the image in RGB format and convert it to grayscale. This means that we will read the image as a three-channel image (red, green, and blue) and then convert it to a single-channel image (black and white).
**2.** Invert the grayscale image. This means that we will swap the black and white pixels.
**3.** Blur the inverted image. This means that we will soften the edges of the image.
**4.** Divide the grayscale image by the blurred inverted image. This means that we will take each pixel in the grayscale image and divide it by the corresponding pixel in the blurred inverted image. This will create the pencil sketch.

The OpenCV library is a powerful library for image processing. It contains many functions for working with images, including the functions that we need to create a pencil sketch.
