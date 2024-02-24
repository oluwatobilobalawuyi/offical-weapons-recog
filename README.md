# Weapons Recognition Program



## How It's Made:

**Tech used:** Python

When constructing the application, I initiated the project by importing DeepFace, cv2, and threading modules and then defining the dimensions of the video window. Once defined, functions that use the DeepFace framework to analyze the video feed and compare the provided information to the reference image provided are created and called. After analyzing and coming to the appropriate response, an option to exit the video windows via the key "q" is made.

## Lessons Learned:

The most integral lesson learned from this project was how to set up a virtual environment like Anaconda properly. Due to the nature of the modules used, it wouldn't be recommended to import the modules to a local desktop directly, and using a virtual environment simplifies and streamlines the process of using the modules. However, due to the Python version used to write the code and other issues like the CV module not being compatible with specific versions of Python, I would have to troubleshoot the virtual environments and the path that the modules were stored in before being able to run the virtual environment and the python program properly.
