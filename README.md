# Hand-Gesture-Project

The program tries to find the number of fingers of your hand. The user have to put ther hand in front of camera and the program gives an output of number of fingers.

### Given:

A set of test images, from no findger to full hand with all fingers.
The images are in the folder.

###program statement

The images are loaded in two image lists. After that they are combined in a list,shuffled and split again. This is done to create test and training images and to create diversity .

The function calc_fingers() returns number of fingers.
The function calculateFingers() proceses the images using OpenCV library, then creates convex hull and contour lines to detect images.

The program uses KNN(K nearest Neighbours) from Scikit-learn library to create prediction model and shows accuracy of the model.

## Basic Usage

Run the file using Jupiter Notebook.
make sure to change the path of image folder,

# Dependencies

[Use pip to install.](https://pypi.python.org/pypi/pip)

1.  Install OpenCV for Python

	[`For Windows`](http://docs.opencv.org/3.1.0/d5/de5/tutorial_py_setup_in_windows.html)

	[`For Ubuntu`](http://www.pyimagesearch.com/2015/06/22/install-opencv-3-0-and-python-2-7-on-ubuntu/)


2. Install scikit-learn 

	Open command prompt and type in:
	```pip install scikit-learn```

3. Install numpy 

	Open command prompt and type in:
	```pip install numpy```
4. Install glob

	Open command prompt and type in:
	```pip install glob```
5. Install OS 

	Open command prompt and type in:
	```pip install os-win```
6. Install Matplotlib 

	Open command prompt and type in:
	```pip install matplotlib```
