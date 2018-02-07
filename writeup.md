# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I make the image blur by Gaussian smoothing,after that I use Canny edge detection to detect edges.Then I use a interest mask to creat an interest region , then I use hough transform to find lane lines

In order to draw a single line on the left and right lanes, I add the generate_result_line() function to draw a single line on the left and right lanes



### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when the car make a turn




### 3. Suggest possible improvements to your pipeline

A possible improvement would be to make the code more robust

