# image_filter

## Description
Sample feature to pull in BMP images and apply a filter to them. The filters available are blur, reflection, sepia, and grayscale. Practice from Harvard CS50 course.

## Use
Clang must be installed

Command Line prompts:

To create exectuable: make filter

To apply filter to image: ./filter -filterOption inputName.bmp outputName.bmp
Example: ./filter -g images/yard.bmp out.bmp
Will apply grayscale filter yard.bmp in images folder into a new bmp known as out.bmp

Filter options:
-b blur
-r reflection
-s sepia
-g grayscale
