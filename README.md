# Gesture Based Tool for Sterile Browsing of Radiology Images

In this project we have used Convolutional Neural Network to first train the model on the images of different hand gestures, like showing numbers with fingers as 0,1,2,3,4,5. Then we made a web portal using Flask where user can input any image on which he wants to perform the operations. After uploading the image, our portal uses the integrated webcam to capture the video frame using OpenCV. The gesture captured in the video frame is compared with the Pre-trained model and the gesture is identified. If the prediction is 0 - then images is converted into rectangle, 1 - image is Resized into (200,200), 2 - image is rotated by -45॰, 3 - image is blurred , 4 - image is Resized into (400,400) , 5 - image is converted into grayscale.

## Flask Folder
- https://drive.google.com/drive/folders/1a6VhgaR2KZcKGkynQw4bOISLd3IT917m?usp=sharing

## Model Building
- https://drive.google.com/file/d/1uYexf8gLwqDxKRuUCAonM81mnIRxPoMv/view?usp=sharing

## Dataset
- https://drive.google.com/file/d/19TYmAbZD1uDvoBJlXbTwosd_i0ibyLiD/view?usp=sharing





