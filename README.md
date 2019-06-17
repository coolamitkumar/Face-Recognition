# Face-Recognition
Recognize and manipulate faces from Python or from the command line with the world's simplest face recognition library.
Built using dlib's state-of-the-art face recognition built with deep learning. The model has an accuracy of 99.38% on the Labeled Faces in the Wild benchmark.

This also provides a simple face_recognition command line tool that lets you do face recognition on a folder of images from the command line!

Installation
Requirements
Python 3.3+ or Python 2.7
macOS or Linux (Windows not officially supported, but might work)
Installation Options:
Installing on Mac or Linux
First, make sure you have dlib already installed with Python bindings:

How to install dlib from source on macOS or Ubuntu
Then, install this module from pypi using pip3 (or pip2 for Python 2):

pip3 install face_recognition
Alternatively, you can try this library with Docker, see this section.

If you are having trouble with installation, you can also try out a pre-configured VM.

Installing on an Nvidia Jetson Nano board
Jetson Nano installation instructions
Please follow the instructions in the article carefully. There is current a bug in the CUDA libraries on the Jetson Nano that will cause this library to fail silently if you don't follow the instructions in the article to comment out a line in dlib and recompile it.
Installing on Raspberry Pi 2+
Raspberry Pi 2+ installation instructions
Installing on Windows
While Windows isn't officially supported, helpful users have posted instructions on how to install this library:

@masoudr's Windows 10 installation guide (dlib + face_recognition)
Installing a pre-configured Virtual Machine image
Download the pre-configured VM image (for VMware Player or VirtualBox).
