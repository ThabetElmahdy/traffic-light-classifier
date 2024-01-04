
# Traffic Light Classification

### A computer vision project to classify traffic light signals as either red, yellow or green.

<p align="center"><img src="https://raw.githubusercontent.com/ShashankKumbhare/traffic-light-classifier/main/auxil/images/all_lights.png"  width="400"></p>

---

## Project Overview

- Traffic light classification plays an important role in Advanced Driver Assist as well as self-driving vehicle systems which ensures timely and appropriate reaction to traffic lights in cross sections.  
- In this project, a robust probabilistic approach based classifier has been implemented from scratch to classify traffic light signal's status using computer vision and machine learning techniques.
- Several data cleaning steps, features extraction and a probabilistic metric has been utilized.
- The classifier has been validated on a testing dataset with a **accuracy of 99.66 %**.
- All training stages and prediction stages has been throughly visualized & analyzed and thus improvised.
- The methodology utilized in this project can be generalized and applied to many other computer vision applications.
- The project presentation notebook is [Notebook Traffic_Light_Classifier](https://github.com/ThabetElmahdy/traffic-light-classifier/blob/main/Traffic_Light_Classifier.ipynb).

---

## Data Description

This traffic light dataset consists of 1484 number of color images in 3 categories - red, yellow, and green. As with most human-sourced data, the data is not evenly distributed among the types. There are:

- 904 red traffic light images
- 536 green traffic light images
- 44 yellow traffic light images

<p align="center"><img src="https://raw.githubusercontent.com/ShashankKumbhare/traffic-light-classifier/main/auxil/images/data_examples.png"  width="600"></p>

Note: All images come from this [MIT self-driving car course](https://selfdrivingcars.mit.edu/) and are licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

- Each image is a numpy array of shape (n_row, n_col, 3) i.e each image has a 3 channels (RGB - red, green, blue color space) where n_col and n_row is the height and the width of the image.
- Each image gives information about its colors of the pixels and their location.
- The RGB color space of the images can be converted to HSV color space channels (hue, saturation, value) i.e. the information about the hue, saturation and brightness of the pixels of the images.




