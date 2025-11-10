# Edge-Linking-using-Hough-Transformm
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## OUTPUT:
 ### INPUT IMAGE:
 <img width="716" height="503" alt="image" src="https://github.com/user-attachments/assets/a77f7903-7de5-499e-aa03-760c777f1938" />

 ### GREYSCALE IMAGE:
 
 <img width="730" height="502" alt="image" src="https://github.com/user-attachments/assets/e2b7ba23-bcc4-4cfe-aee5-9913e2fca635" />

 ### Canny Edge detector output:
 <img width="699" height="504" alt="image" src="https://github.com/user-attachments/assets/6d85bd00-e110-4698-b3ae-ebb88bfe8593" />

### Display the result of Hough transform
<img width="694" height="495" alt="image" src="https://github.com/user-attachments/assets/3510c3a1-22e4-4b01-9c08-1308bcb58772" />


## Result:
Thus the program is written with Python and OpenCV to detect lines using Hough transform.

