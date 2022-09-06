---
layout: single
permalink : /CPW11/
title:  "Coding Period - Week 11"
categories: jekyll update
toc: true
toc_label: Table of Content
sidebar:
  nav: "docs"
---
For this week, I decided to go for some other exercise that have the most different pattern from the other exercise. For this I used the exercise detials list to find the anamoly. I found that the **DL Digit classifier ** exercise has a different pattern. So, I decided to go ahead with the DL digit classifier exercise.

### Goals

- [x] DL Digit classifier Exercise

- [x] Atomize the exercise control widgets

- [x] Categorizes the different components into sub-directories

### Accomplishment and Challenges


* #### DL Digit classifier Exercise \[Task 1\]

Components that are different in this exercise are -

1. Exercise control widget - The observed difference is that the exercise control widget is not common for every exercise. It is a separate widget that is used to control the exercise. Though Every exercise utilize this widget, the way it is used is different in every exercise. So, I had to make a separate widget for each exercise. This is a good thing as it will help in making the exercise more modular and reusable. For the case of DL Digit classifier exercise, I had to make a separate widget for the exercise control as it required only the PlayStop button and the Reset button. The other buttons like Load file, Save file, view Sim button and load into robot button are not required for this exercise. So, I had to make a separate widget for this exercise.

2. File Selector - The file selector is a widget that is used to select the file from the local system. This widget is used to load the Onnx format model for the exercise. To make the widget more modular and reusable,  The props that are passed to the widget are the context, file ref, file type, the file extension, the file name and the callback function. The callback function is used to pass the selected file to the parent component. 
3. Gazebo - There is no gazebo required for this exercise hence the Gazebo widget is not required for this exercise.

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/digit_classifier.png" alt="" class="full">


* #### Atomize the exercise control widgets \[Task 2\]

As Observed in the previous exercise, the exercise control widget is not common for every exercise. It is a separate widget that is used to control the exercise. Though Every exercise utilize this widget, the way it is used is different in every exercise.
The common pattern for exercise control are -
1. Exercise Control \[ FULL FUNCTIONALITIES \] - It consists of functionalities like PlayStop, Reset, Load file, Save file, load into robot, gui frequency slider, brain frequency slider, view Sim, view Gazebo and teleop.
2. Exercise Control \[ No TeleOp  \] - It consists of functionalities like PlayStop, Reset, Load file, Save file, load into robot, gui frequency slider, brain frequency slider, view Sim and view Gazebo.

So for this approach I created all buttons as separate widget considering the scope of future changes.

This is a good thing as it will help in making the exercise more modular and reusable.


* #### Categorizes the different components into sub-directories \[Task 3\]

After migrating several exercises there were many components clubbed together in a single folder which may cause hindrance to the exercise developer in making the exercise.

Considering the future prospect of the project, I built the components but a structural representation will make the process more subtle and fast.

Components were divided into the categories written below -

1. Views - different views for exercises and also consisting of forum and theory view,
2. Modals - Load modal, Info modal and Error Modal,
3. Common - components common for every exercise,
4. exercise - components that specific to the exercise,
5. buttons - buttons that are utilize in an exercise,
6. visualizers - different visualizers were created for differnt exercise and 
7. templates - Main Body of the exercises that are rendered by the Django server.


NOTE: As explained in previous weeks, exercise was broken down into three views - exercise, theory and forum.
So all different views were stored in the views folder

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/file_structure.png" alt="" class="full">


### Achievements

🎉🎊🙌🏻 DL Digit classifier Exercise Completely migrated and working perfectly. 🎉🎊🙌🏻 

<!-- * Exercise - [Follow Line React](https://youtu.be/YMMQVo_3oh8)

<iframe width="420" height="315" src="https://www.youtube.com/embed/YMMQVo_3oh8" frameborder="0" allowfullscreen></iframe> -->