## Dylan Sheldon - University Of Gloucestershire

### About me

I am currently studying BSc Applied Artificial Intelligence at the University Of Gloucestershire. I am also a Course Representative within the students union which improves my skills and coordination in multiple areas. My LinkedIn page can be viewed [here](https://www.linkedin.com/in/dylan-sheldon-0378281b9/)

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

The Test, Train and Validation sets were already seperated into 2 duplicate folders. One was used for the original Training to gauge a baseline and then another to add Augmented images for further training. Initially, the predictions were not accurate on the unmodified dataset. The model was confusing scissors for hands. I tried finding the optimum learning rate which proved to be inaffective when predicting on the Validation set. The first learner produced inconsistent graphs when training. After trying larger image sizes, the model seemed to improve slightly but not enough. I then tried Image Augmentation with SciKit-Image. I created 2 functions, One to randomly rotate an image, and the other to iterate over a given Directory of images and return new copies of the images with random rotations. This took Approximately 8 mins to run and generated 2157 images, doubling the starting total. Using this expanded set improved the accuracy of the predictions significantly, which also used a larger resnet size of 50 instead of 32, which guessed only 3 wrong out of the 33 in the validation set. Which resulted in an accuracy of 90.91%.
The completed notebook can be viewed [here](https://github.com/sheldyso/Rock-Paper-Scissors-CNN/blob/main/Rock_Paper_Scissors_CNN.ipynb).

### Semester 2 - SciKit-Learn Data Insights and Visualisation

**Current Assignment**

## Systems Design and Development

### Semester 1 - Business Report

For this assignment, I had to create a business report on a project that would utilise data which was a customer personality analysis dataset. To explore the dataset, I opened a Jupyter notebook and used pandas to import the csv dataset and look at the features. I concluded that the machine learning application of the dataset would be to create a model based off their type of purchases and find patterns. This could be done with unsupervised learning such as clustering. The model would then be used in a mobile shopping application to create targeted ads or personalised shopping lists. As part of the report, I explored the dataset requirements with ethical consideration, database design, Software Development methodology, software and hardware requirements, costing and staffing, and finalised with legal considerations. The business report can be found [here](https://github.com/sheldyso/sheldyso.github.io/blob/main/Business%20Report.pdf).

### Semester 2 - Implementing a Database with Machine Learning / Data science Pipeline

**Current Assignment**

## Programming Alogrithms and Techniques

### Semester 1 - ASCII Game Engine ( C++ )

In this assignment, I had to create an approximation of the classic 1979 Atari game, "Lunar Lander" with a supporting video to show the gameplay.

The following libraries were used:

- Windows.h
- string
- chrono

Initially, the game was developed inside of Main.cpp, whilst this helped to set out the initial structure, it cluttered the overall code and needed to be seperated into the appropriate files. I created a Game.cpp file that contained the game logic to reduce the size of Main.cpp. 
Additional Header files were also made:

- Constants.h
- Utility.h
- GameObjects.h
- Game.h

Whilst being tasked to make a Game to demonstrate skills in the assignment, important points were taken from this. Such as:

- Code structure
- Adding and using libraries
- Seperating code into headers and linking them
- Using structs to create objects
- Structuring Application states

This VS project can be found [here](https://github.com/sheldyso/ASCII-Lunar-Lander).

### Semester 2 - Retro Arcade Classic ( C++ )

This assignment requires use of a single header Game library developed by Sumo Digital called the "PlayBuffer" library.

**Current Assignment**

## Programming and Mathematics

### Semester 1 - Clay Pigeon Shooting Simulation ( Unity,  C# )

For this assignment, the goal was to program projectile motion using SUVAT equations and interception calculations to create projectiles which would be targeted by a main cannon. I had to create my own classes to be used instead of the proprietary Unity classes which would include their own Dot product, Cross Product, Magnitude, Rotation and Vector Conversion functions.

### Semester 2 - Math(s) Library and Unity Tanks Scene

**Current Assignment**

## Students' Union Course Representative

Alongside my studies, I opted to be the Course Representative for Level 4 (BSc) Applied Artificial Intelligence. This role came with a vast amount of learning opportunities and multiple responsibilities.

### Role:
As a Course Representative, I have to take Feedback from my Course-mates as needed and then depending on the matter raised, respond to the Student Subject Coordinator or the Academic Course Leader. There are also Crucial meetings the University Organise on a semester basis. Each Semester Contains an Academic Subject leader meeting and Creative Computing Course Conference where student feedback is discussed, course changes are mentioned and other matters regarding IT or library services.

## Additional Projects

### Certifications

I am currently working towards a certificiation with [FreeCodeCamp](https://www.freecodecamp.org/learn/) on Scientific Computing with Python. Once completed, the certification will be available to view on LinkedIn. I also plan to complete the Data visualisation certification as it strongly coincides with my current studies in my Systems Design and Development and Introduction to AI module.

### Gloucestershire Employability Award : Bronze

I am currently working towards my Bronze Employability award as part of the University of Gloucestershires Future Plan extra-carricular and skills development achievements. The bronze award consists of 4 main sections:

- Attend 5 workshops or resources.
- Log 20 Hours of Professional Development or work experience
- Complete a career readiness report 
- Write a reflection on the preceeding tasks

For my 20 hours, I logged 1 hour for my course representative role as I took part in the course conference and held discussions in class with the Course leader and students. For the remaining 19 hours, The development of this placement portfolio will go towards my professional development.
