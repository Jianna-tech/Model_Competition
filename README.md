# Model_Competition

*Subject Matter: The project will focus on an application requiring image recognition. We will construct a variety of machine learning models with the goal of 
 generating predictive classifications.

*The Data: The MNIST Fashion database (https://github.com/zalandoresearch/fashion-mnist (Links to an external site.)) collected a large number of images for different types
 of apparel. Each image is divided into small squares called pixels of equal area. Within each pixel, a brightness measurement was recorded in grayscale. The brightness 
 values range from 0 (white) to 255 (black). The original data set divided each image into 784 (28 by 28) pixels. To facilitate more tractable computations, we have 
 condensed   these data into 49 pixels (7 by 7) per image. An example of dividing an image into a different quantity of pixels is depicted in the Images below.
 
 * Points = 0.15 * A + 0.1 * B + 0.75 * C where

 * A is the proportion of the training rows that is utilized in the model. For instance, if you use 30,000 of the 60,000 rows, then A = 30,000 / 60,000 = 0.5;

 * B = min (1, X60), where X is the running time of the selected algorithm in seconds. Algorithms that take at least 1 minute to run will have the value B = 1, which incurs the      full run-time penalty.

 * C is the proportion of the predictions on the testing set that are incorrectly classified. For instance, if 1000 of the 10000 rows are incorrectly classified, then C = 1000 /      10000 = 0.1.

WE createD and evaluated different machine learning models on different sample sizes. The quality of different combinations of the models, their running times, and the sample sizes can be compared based on their Points. The overall goal is to build a classification method that minimizes the value of Points. In this setting, the ideal algorithm would use as little data as possible, implement the computation as quickly as possible, and accurately classify as many items in the testing set as possible. 
