
A basic deep learning project

Technology used-Python

Model used-Deep Neural Network(Deep Learning Model)(DNN)

Librares used- numpy,imutils,cv2,time

This project is a simple Obeject recognition using pre-trained with DNN using Open-CV.

Just a simple briefing about the code-

Starting off, we load our neccessary libraries and our MobileNetSSD model for the object detection. Then we Then we help the machine to access aur webcam through which the pretrained model will detect the objects. Then we lead the machine to scan each frame of the webcam and after scanning the machine would resize the image in a 300 x 300 format and then would convert the image into a blob image for better recognition. Then we provide it with a confidence level so that whatever it detect except for the still background, the obejct would be put into a rectangular frame for our visual understanding purpose.

That is it for the code explanation, just for a bit more simplicity i also included in the code that after the rectangle is formed around the object the name and the confidence level is also shown on the screen.


