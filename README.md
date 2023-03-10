# Traffic-Light-Classifier
build a classifier for images of traffic lights, where it distinguishes the different types of images, and use those features to classify these images into three classes: red, yellow, or green

## Installing Dependencies
* opencv  -  `pip install opencv-python `


## Sample from the data
![sample](images/all_lights.png) 

## Classification Steps

* **Loading and Visualizing the Traffic Light Dataset**

    This traffic light dataset consists of 1484 number of color images in 3 categories - red, yellow, and green. As with most human-sourced data, the data is not evenly distributed among the types. There are:

    - 904 red traffic light images
    - 536 green traffic light images
    - 44 yellow traffic light images

    _Note: All images come from this [MIT self-driving car course](https://selfdrivingcars.mit.edu) and are licensed under a 9Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/)._
