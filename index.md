## Dylan Sheldon - University Of Gloucestershire

### About me

For my degree, I am currently studying BSc Applied Artificial Intelligence at the University Of Gloucestershire.

## Level 4

At level 4, I had 8 Assignments in 4 modules spread across 2 semesters.

## Introduction to AI

### Semester 1 - Training a Fastai Convolutional Neural Network

In this module, I used a rock, paper, scissors image dataset and created mutiple CNN learners to explore different methods of improving the accuracy of the predictions. This was done in a Jupyter notebook using google colaboratory for the training. This was also paired with SciKit-image. The following libraries were used:
- numpy
- pandas
- os
- fastai
- skimage
- random

The Test, Train and Validation sets were already seperated into 2 duplicate folders. One was used for the original Training to gauge a baseline and then another to add Augmented images for further training. Initially, the predictions were not accurate on the unmodified dataset. The model was confusing scissors for hands. I tried finding the optimum learning rate which proved to be inaffective when predicting on the Validation set. The first learner produced inconsistent graphs when training. After trying larger image sizes, the model seemed to improve slightly but not enough. I then tried Image Augmentation with SciKit-Image. I created 2 functions, One to randomly rotate an image, and the other to Iterate over a given Directory of images and return new copies of the images with random rotations. This took Approximately 8 mins to run and generated 2157 images, doubling the starting total. Using this expanded set improved the accuracy of the predictions significantly, which also used a larger resnet size of 50 instead of 32, which guessed only 3 wrong out of the 33 in the validation set. This results in an accuracy of 90.91%.
The completed notebook can be viewed [here](https://github.com/sheldyso/Rock-Paper-Scissors-CNN/blob/main/Rock_Paper_Scissors_CNN.ipynb).

### Semester 2 - SciKit-Learn data insights and visualisation

## Systems design and development

### Semester 1 - Business Report

For this assignment, I had to create a business report on a project that would utilise a given dataset which was a customer personality analysis dataset from [kaggle](https://www.kaggle.com/imakash3011/customer-personality-analysis).

### Semester 2 - 

## Programming alogrithms and techniques

### Semester 1 - ASCII Game Engine

### Semester 2 - 

## Programming and mathematics

### Semester 1 - Clay Pigeon Shooting Simulation

### Semester 2 - 

## Additional Projects

### Flower Recognition



### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
