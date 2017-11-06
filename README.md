# **Finding Lane Lines on the Road** 

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./readme_image/grayscale.png "Grayscale"
[image2]: ./readme_image/gaussian_blur.png "Gaussian Blur"
[image3]: ./readme_image/interests.png "Interests"
[image4]: ./readme_image/canny.png "Canny"
[image5]: ./readme_image/result.png "Result"

---

### Reflection

### 1. Steps to find lane line on the road

#### a). Gray scale the image
Uses the function from openCV to gray scale image.
![alt text][image1]
#### b). Gaussian blur the gray scaled image
Uses the function from openCV to Gaussian blur image.
![alt text][image2]
#### c). Use hough transform to find lines
Uses the function from openCV to hough transform image.
![alt text][image4]
#### d). Find the regions of interest
Uses the function from openCV to find the region of interest image.
![alt text][image3]
#### e). Draw lines to the original image
Draw lines that we found from regions of interest
![alt text][image5]


### 2. Identify potential shortcomings with your current pipeline

When the road is turning, the line image will have some noices.


### 3. Suggest possible improvements to your pipeline


