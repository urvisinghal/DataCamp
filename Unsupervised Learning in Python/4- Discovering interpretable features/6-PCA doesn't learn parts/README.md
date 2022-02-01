PCA doesn't learn parts

Unlike NMF, PCA doesn't learn the parts of things. Its components do not correspond to topics (in the case of documents) or to parts of images, when trained on images. Verify this for yourself by inspecting the components of a PCA model fit to the dataset of LED digit images from the previous exercise. The images are available as a 2D array samples. Also available is a modified version of the show_as_image() function which colors a pixel red if the value is negative.

After submitting the answer, notice that the components of PCA do not represent meaningful parts of images of LED digits!

<br>

Instructions

Import PCA from sklearn.decomposition.

Create a PCA instance called model with 7 components.

Apply the .fit_transform() method of model to samples. Assign the result to features.

To each component of the model (accessed via model.components_), apply the show_as_image() function to that component inside the loop.
