Explore the LED digits dataset

In the following exercises, you'll use NMF to decompose grayscale images into their commonly occurring patterns. Firstly, explore the image dataset and see how it is encoded as an array. You are given 100 images as a 2D array samples, where each row represents a single 13x8 image. The images in your dataset are pictures of a LED digital display.

<br>

Instructions

Import matplotlib.pyplot as plt.

Select row 0 of samples and assign the result to digit. For example, to select column 2 of an array a, you could use a[:,2]. Remember that since samples is a NumPy array, you can't use the .loc[] or iloc[] accessors to select specific rows or columns.

Print digit. This has been done for you. Notice that it is a 1D array of 0s and 1s.

Use the .reshape() method of digit to get a 2D array with shape (13, 8). Assign the result to bitmap.

Print bitmap, and notice that the 1s show the digit 7!

Use the plt.imshow() function to display bitmap as an image.
