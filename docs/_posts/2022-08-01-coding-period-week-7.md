---
layout: single
permalink : /CPW7/
title:  "Coding Period - Week 7"
categories: jekyll update
toc: true
toc_label: Table of Content
sidebar:
  nav: "docs"
---
Now with the Exercise being completely refractored and working, Some Modals like the Info Modal and the Error Modal were left to implement. So Discussed to finish them in order to wrap the exercise completely. To plan out the implementation of the remaining exercise, Now to was important to classify the exercise into categories.

### Goals

- [x] Error Modal View

- [x] Info Modal View
 
- [x] Exercise Details List

### Accomplishment and Challenges 

* #### Error Modal \[Task 1\]
This is a dynamic widget which shows all the errors that are generated during the execution of the code.
<img src="{{ site.url }}{{ site.baseurl }}/assets/images/errormodal.png" alt="" class="full">

* #### Info Modal \[Task 2\]
This modal shows the users about all the controls available to the user, which helps the user to understand the functionality of the application.
<img src="{{ site.url }}{{ site.baseurl }}/assets/images/infomodal.png" alt="" class="full">

* #### Exercise Details List Sheet \[Task 3\]

Exercise can be broken down into two major components -

**Functionals components:** In functionalities there is one more breakdown for every exercise which is unique to exercise.

  * **Common Functions:**  common Javascript file shared by different components
  * **Exercise Specific Functions:** Javascript file specific to the exercise.


**UI components (React):**

HTML does not have a concept of components.Same components is written multiple times for several exercises.

But in case of React, we can reuse the components if common between the exercises.

So, In order to maintain and migrate the exercises into Advanced frontend technology (React) - a documentation defining this would help ease the task.

**Sheet Link - [Exercises Sheet](https://docs.google.com/spreadsheets/d/1ZpZhbbFHv96CvQ57HjU6g9WmFd-_1QKq_EAjZLRB6eY/edit?usp=sharing)**


### Issues 

1. [#1801](https://github.com/JdeRobot/RoboticsAcademy/issues/1801)

### Pull Requests
