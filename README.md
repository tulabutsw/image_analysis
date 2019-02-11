# image_analysis

# image_segmentation_and_stats.m
This MATLAB script is used for the image processing described in Yang et al. Cell 2019.  

## Method
The script takes as an input a fluorescence channel image that has Pbp1-GFP expressed in the cytoplasm. First, it segments the cell cytoplasm by global intensity thresholding using Otsu’s method. Next, it returns the mean, standard deviation and coefficient of variation of the pixel intensities that make up the cytoplasm.

## Requirements
The code is implemented in MATLAB 2018a. It is not tested on earlier versions of MATLAB. 
Image Processing Toolbox is required.

## Usage
Run under the folder containing the script and the two example images. The default script runs with the first example image. To run the second example image, comment out line 20, and uncomment line 22.  

If you have questions or problems, please do not hesitate and contact us at Benjamin.Tu@UTSouthwestern.edu . We will be glad to help.
