# GIFs-with-python

Imports imageio.v3 for image processing.
Defines a list of image filenames to combine.
Initializes an empty list to store image data.
Reads each image using iio.imread() and appends to the list.
Writes all images into a single GIF file (team.gif).
Sets frame duration to 500 ms (0.5 sec per frame).
Sets loop to 0, meaning the GIF plays infinitely.
