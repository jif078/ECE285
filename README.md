# ECE285

Description
===========
This is project UCSD_2018_Spring-ECE285(ML for Image Processing) developed by team MLers 
composed of Anh Mai, Jinzhao Feng, Minhong Zhou, Steven Tien

Requirements
============
Install package 'matplotlib ' as follow :          
$ pip install -- user matplotlib         

Install package 'scipy ' as follow :      
$ pip install -- user scipy

Install package 'PIL ' as follow :
$ pip install -- user pillow

Install package 'tensorflow ' as follow :
$ pip install -- user tensorflow

To use the VGG modude users need to download the pretrained matrix "imagenet-vgg-verydeep-19.mat". The file is big(510Mb), so we will attach it along with the project in the email. Please download the matrix in your module before running the code
The matrix can also be dowloaded directly from http://www.vlfeat.org/matconvnet/pretrained/

Code organization
=================
ECE285_main. ipynb -- Run the style transfer transfer module and produce figure 6 (b) in our report(take less than 2 munite to run). The same module can produce all the results we show in the report. There are comment along with the prarameters to produce each case. In some case, it may take more an 30 munites to produce the result.

images /... folder that contains all the inputs of content and style images for different cases

output/... -- folder that contain the result generated image 
