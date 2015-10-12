# img
An image viewer python script

Usage:
You can pass either an image, a directory, or nothing (dislpays current directory).
Press the arrow keys to view other images in the directory of the image/directory passed

Supports everett1992 wp script (https://github.com/everett1992/wp)
Use the spacebar for wp change [current image] and the return key for wp add [current image]

Requires Tkinter and PILLOW to run
TODO:

	1. Make the background transparent(not possible with tkinter, requires different gui manager)
	2. Get things to be not in one file. This requires not using globals anymore(shouldn't do that anyway)
