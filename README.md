# 20182_cstopics_HandDetect_MoveCursor
Hand Detect that move cursor, python project 

University Santo Tomas
Faculty of Engineering Electronic

Miguel Elkin Jimenez Avila 
Santiago Mateo Guerrero Romero
Camila Alejandra Plazas Oviedo


# Description of project
This project is a hand detect that move the cursor according to position of hand, also detect fist and the program do click.

We used a classifier to the detection hand and fist, this classifier is a CNN (Convolution Neuronal Network).

We used a color filter to the localitation hand and fist, this filter take the yellow color. 

Next we going to show the flow diagram:
https://user-images.githubusercontent.com/45437733/49184484-811c6600-f32d-11e8-9c32-eeebf6808157.jpg
![diagrama](https://user-images.githubusercontent.com/45437733/49232259-9d69e280-f3c1-11e8-9efb-2bff439234ce.jpg)


We use Tensorflow to create CNN, this net have 4 layers. Information for CNN:
https://user-images.githubusercontent.com/45437733/49190063-ca28e600-f33e-11e8-8f11-6c620e2263fb.JPG
Information for trainning:  
https://user-images.githubusercontent.com/45437733/49190083-dd3bb600-f33e-11e8-8ace-c7b6316bf699.JPG

The filter is a band-pass filter to the yellow color, because we used a yellow glove to does easy localization process.

# Images samples
Detect open hand and location in the screen, get position of the hand and set position of the cursor.
https://user-images.githubusercontent.com/45437733/49186377-76180480-f332-11e8-8a70-4ce95874d5e0.png

Detect the fist and does click.
https://user-images.githubusercontent.com/45437733/49186418-95af2d00-f332-11e8-833a-4d42d40f982f.png

# Steps for run program:

1. In your terminal, you go to folder "DetectHand".
2. Run this line python test2.py
3. Put the yellow glove 
4. Try to move the cursor and then try to do click 

# Dependencies:

- cv2
- tensorflow
- keras
- numpy
- scipy 
- os
- re
- glob
- os.path
- matplotlib
- imutils
- collections
- autopy

# link Video in Youtube

https://youtu.be/4wgnDpHvBiI
