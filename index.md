## Dylan Sheldon - University Of Gloucestershire

### About me

For my degree, I am currently studying BSc Applied Artificial Intelligence at the University Of Gloucestershire.

## Level 4

At level 4, I have 8 Assignments in 4 modules spread across 2 semesters.

## Introduction to Artificial Intelligence

### Semester 1 - Training a Fastai Convolutional Neural Network ( Jupyter NoteBook )

For this assignment, I used a rock, paper, scissors image dataset and created mutiple CNN learners to explore different methods of improving the accuracy of the predictions. This was done in a Jupyter notebook using google colaboratory for the training. This was also paired with SciKit-image. The following libraries were used:
- numpy
- pandas
- os
- fastai
- skimage
- random

The Test, Train and Validation sets were already seperated into 2 duplicate folders. One was used for the original Training to gauge a baseline and then another to add Augmented images for further training. Initially, the predictions were not accurate on the unmodified dataset. The model was confusing scissors for hands. I tried finding the optimum learning rate which proved to be inaffective when predicting on the Validation set. The first learner produced inconsistent graphs when training. After trying larger image sizes, the model seemed to improve slightly but not enough. I then tried Image Augmentation with SciKit-Image. I created 2 functions, One to randomly rotate an image, and the other to Iterate over a given Directory of images and return new copies of the images with random rotations. This took Approximately 8 mins to run and generated 2157 images, doubling the starting total. Using this expanded set improved the accuracy of the predictions significantly, which also used a larger resnet size of 50 instead of 32, which guessed only 3 wrong out of the 33 in the validation set. This results in an accuracy of 90.91%.
The completed notebook can be viewed [here](https://github.com/sheldyso/Rock-Paper-Scissors-CNN/blob/main/Rock_Paper_Scissors_CNN.ipynb).

### Semester 2 - SciKit-Learn data insights and visualisation

**Current Assignment**

## Systems design and development

### Semester 1 - Business Report

For this assignment, I had to create a business report on a project that would utilise a given dataset which was a customer personality analysis dataset. The business report can be found [here](https://github.com/sheldyso/sheldyso.github.io/blob/main/Business%20Report.pdf).

### Semester 2 - 

## Programming alogrithms and techniques

**Current Assignment**

### Semester 1 - ASCII Game Engine ( C++ )

In this assignment, I had to create an approximation of the classic 1979 Atari game, "Lunar Lander" with a supporting video to show the gameplay.

The following libraries were used:
- Windows.h
- string
- chrono

Initially, the game was developed inside of Main.cpp, whilst this helped to set out the initial structure, it cluttered the overall code and needed to be seperated into the appropriate files. I created a Game.cpp file that contained the game logic to reduce the size of Main.cpp. Additional Header files were also made:
- Constants.h
- Utility.h
- GameObjects.h
- Game.h

Whilst being tasked to make a Game to demonstrate skills in the assignment, important points were taken from this. Such as:

- Code structure
- Adding and using libraries
- Seperating code into headers and linking them
- 

This VS project can be found [here](https://github.com/sheldyso/ASCII-Lunar-Lander).

### Semester 2 - Retro Arcade Classic ( C++ )

This assignment required use of a single header Game library developed by Sumo Digital called the "PlayBuffer" library.

**Current Assignment**

## Programming and mathematics

### Semester 1 - Clay Pigeon Shooting Simulation ( Unity C# )

For this assignment, I had to create my own Vector 2 and 3 classes 

### Semester 2 - 

**Current Assignment**

## Students' Union Course Representative

Alongside my studies, I opted to be the Course Representative for Level 4 (BSc) Applied Artificial Intelligence. This role came with a vast amount of learning opportunities and multiple responsibilities.
### Role:
As a Course Representative, I have to take Feedback from my Course-mates as needed and then depending on the matter raised, respond to the Student Subject Coordinator or the Academic Course Leader. There are also Crucial meetings the University Organise on a semester basis. Semester 1 Contained an Academic Subject leader meeting and Creative Computing Course Conference.

## Additional Projects
