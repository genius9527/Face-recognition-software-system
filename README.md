![](https://img.shields.io/badge/download-4M-brightgreen.svg)
# Face-recognition-software-system
A face recognition software system, using QT design interface, face recognition using dlib-face, face detection using OpenCV's Haar classifier.It is divided into registration module, home page and login module, in which the registration module also contains authentication module. In addition, there are two kinds of collection methods of registration set and authentication set.One is camera shooting, and the other is local photo upload.  
**Software Environment:**  
opencv3.0,QT5.5,Python2.7.13,ubuntu14.04  
**Steps for usage：**  
1.Download the code and change the path,such as the location of the classifier file for opencv, the location of the registration set and the identity set, and so on.  
2.Install the face_recognition module for python,and you can install it by following commands：`pip2 install face_recognition` or download the `face_recognition-0.1.14-py2.py3-none-any.whl` from https://pypi.python.org/pypi/face_recognition or compile the source code.  
3.You need to put the `dlib_face_recognition.py` into the python library,such as `sudo cp /home/hanlifu/dlib_face_recognition.py /usr/lib/python2.7/dlib_face/recognition.py`.  
**Effect display：**  
`Whole_function`  
![](https://github.com/genius9527/Face-recognition-software-system/tree/master/effect_photo/Whole_function.jpg)  
