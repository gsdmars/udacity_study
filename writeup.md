# **Finding Lane Lines on the Road** 

## Writeup

[//]: # (Image References)

[image1]: ./test_images_output/solidWhiteCurve.jpg "solidWhiteCurve"
[image2]: ./test_images_output/solidWhiteRight.jpg "solidWhiteRight"
[image3]: ./test_images_output/solidYellowCurve.jpg "solidYellowCurve"
[image4]: ./test_images_output/solidYellowCurve2.jpg "solidYellowCurve2"
[image5]: ./test_images_output/solidYellowLeft.jpg "solidYellowLeft"
[image6]: ./test_images_output/whiteCarLaneSwitch.jpg "whiteCarLaneSwitch"

### Reflection

My pipeline consisted of 6 steps. 
The function line\_detect implements it.
First, I converted the images to grayscale, then filter the images noise by gaussian\_blur, then detect lane lines by canny, then get interest region by region\_of\_interest, then pick hough point by hough_lines, then draw line by draw\_lines, then merge the image with interest region 

![alt text][image1]
![alt text][image2]
![alt text][image3]
![alt text][image4]
![alt text][image5]
![alt text][image6]


