# Face-Detection-and-Recognition
A simple implementation of Face Detection and Face Recognition using Python OpenCV :desktop_computer:

1. Development Environment
2. Install Python
3. Install numpy
4. Install OpenCV
5. Install Pillow
6. Common Errors I Faced
7. Resources


## Development Environment
- OS: Windows 10
- IDE: PyCharm
- External Peripharals: Internal + External Webcam

## Install Python
You can Download and Install python from the following link: <a href="https://www.python.org/downloads/"> Download Python </a>

## Install numpy
Use the following command in Command Prompt (Administrator) to install numpy in your System<br>
> pip install numpy

## Install openCV
Use the following command in Command Prompt (Administrator) to install openCV in your System<br>
> pip install opencv-python

## Install Pillow
Use the following command in Command Prompt (Administrator) to install Pillow in your System<br>
> pip install Pillow

## Common Errors Faced
```
Invalid HAAR feature (expected: 'rw.r.x < W'), where
>     'rw.r.x' is 17<br>
> must be less than<br>
>     'W' is 15
```

You will find a `<size></size>` tag inside of the metioned HAAR .xml file, It Contains the Width-W, and Height-H, making either of the needed value greater than the required value helps. (basically 32)

## Resources
- Know more about OpenCV: <a href="https://opencv.org/"> OpenCV </a>
- Know more about HAAR-Cascades: <a href="https://www.bogotobogo.com/python/OpenCV_Python/python_opencv3_Image_Object_Detection_Face_Detection_Haar_Cascade_Classifiers.php"> Haar Cascades</a>
- Where to search for python libraries: <a href="https://pypi.org/"> pypi.org </a>
- HaarCascade OpenCV files: <a href="https://github.com/opencv/opencv/tree/master/data/haarcascades"> Click here<a/>
- HaarCascade SimpleCV files: <a href="https://github.com/sightmachine/SimpleCV/tree/master/SimpleCV/Features/HaarCascades"> Click here </a>
