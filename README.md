# Snapchat-Filter

In this project, Using libraries numpy, cv2 and pre-trained haarcascade models for face and eye detection, Making of filter that places a transparent sun-glasses of size propotional to face in live video stream recorded through web-cam was accomplished.

This project was learnt in Image-Processing SMP conducted by ISTE-NITK chapter.

## Objective
- To write a python code to create a filter which puts a sunglasses on your eyes.

## Components of Code 

- Import the required libraries : cv2,numpy
- Import the pre-trained models for face and eye detection
- Start video capture
- Detect faces on each frame of the captured video
- Find the bounding boxes
- Find facial landmarks
- Resize the glasses to match the face width
- Blend the glasses in the right position

### Operation:
-->Modify the path for sunglasses.png and voila!

-->Sometimes tweaking scale factor of detectMultiScale() will help If the code doesn't work. (imp: scalefactor>1 eg:1.05, 1.15, 1.2)

#### FAQs
-->What is an alpha channel? Normally, images have three channels: red, green, and blue. These denote the default color space; however, some images have a fourth channel, called the alpha channel, which denotes transparency.
-->When I drew the pair of sunglasses, I ensured it contained a transparent background. Normally, OpenCV would ignore this, but by passing -1 into the imread method, it reads this fourth channel.

-->Destination matrix conflict:While the eyes are detected, there’s no way of knowing the order of the eyes in advance. Sometimes the right eye will be detected first and sometimes the left eye will. To test, the x-coordinate is compared between the two eyes, and then the proper destination matrix can be composed.

.
.
.




| Certificate | [https://drive.google.com/file/d/1PEJNU2x3SOujFg-tOsKhXY9AHo9kYEto/view?usp=sharing][PlDl] |






   [PlDl]: <https://drive.google.com/file/d/1PEJNU2x3SOujFg-tOsKhXY9AHo9kYEto/view?usp=sharing>
  
