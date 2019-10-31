## Objective:
Image demosaicing is an algorithm used to convert grayscale/raw images into color images. Histogram manipulation helps in adjusting contrast of grayscale using its histogram of pixel intensities. Here I have implemented two different types of Image demosaicing:
1. Bilinear Demosaicing
2. MHC Demosaicing
as well as two Histogram Manipulation methods:
1. Bucket Filling Method
2. Cumulative Frequency Distribution Method

Image Denoising is the process of removing noise from image. It is an important preprocessing step for further image analysis. Different types of noise that can corrupt image are Gaussian noise, uniform noise, impulse noise, etc. To deal with each of them we have different filters. In this project, I have implemented the following filters on grayscale as well as color images and observe the performance with each of them:

1. Linear filter
2. Bilateral filter
3. Non-local mean (NLM) filter 

## Project:

For Each Question, Parameters to be passed : 

input_file_name output_file_name

I have hard-coded the Program to handle particular Input Images. 
For example, for Demosaicing using Bilinear Interpolation Question, Input image size  = 390 * 300 BW Image. 
So, I have handled the size and format of the image in the main function. 
Like while reading cat.raw image, code reads[390][300][1].

Same applies to all the questions. 

So, for example, for Q1.(a) Parameters Passed will be
* g++ bilinear.cpp -o main
* main cat.raw bilinear_cat.raw
