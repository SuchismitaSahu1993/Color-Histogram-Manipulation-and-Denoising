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
