# Color Conversion
## AIM
To perform the color conversion between RGB, BGR, HSV, and YCbCr color models.

## Software Required:
Anaconda - Python 3.7
## Algorithm:
### Step1:
<br>

### Step2:
<br>

### Step3:
<br>

### Step4:
<br>

### Step5:
<br>

## Program:

### Developed By: S.ABHISHEK
### Register Number: 212221230002
### i) Convert BGR and RGB to HSV and GRAY
```
import cv2
img = cv2.imread('a.jpg')
cv2.imshow('original image',img)
hsv_image = cv2.cvtColor(img,cv2.COLOR_BGR2HSV)
cv2.imshow('BGR2HSV',hsv_image)
hsv_image1 = cv2.cvtColor(img,cv2.COLOR_RGB2HSV)
cv2.imshow('RGB2HSV',hsv_image1)
gray_image = cv2.cvtColor(img,cv2.COLOR_BGR2GRAY)
cv2.imshow('BGR2GRAY',gray_image)
gray_image1 = cv2.cvtColor(img,cv2.COLOR_RGB2GRAY)
cv2.imshow('RGB2GRAY',gray_image1)
cv2.waitKey(0)
cv2.destroyAllWindows()
```


### ii)Convert HSV to RGB and BGR





### iii)Convert RGB and BGR to YCrCb




### iv)Split and Merge RGB Image




### v) Split and merge HSV Image





## Output:
### i) BGR and RGB to HSV and GRAY
![image](https://user-images.githubusercontent.com/66360846/226851037-e2b7324f-8e35-44a7-bb7a-5c4baf3303c1.png)

### ii) HSV to RGB and BGR
<br>
<br>

### iii) RGB and BGR to YCrCb
<br>
<br>

### iv) Split and merge RGB Image
<br>
<br>

### v) Split and merge HSV Image
<br>
<br>


## Result:
Thus the color conversion was performed between RGB, HSV and YCbCr color models.
