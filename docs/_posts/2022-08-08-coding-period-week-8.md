---
layout: single
permalink : /CPW8/
title:  "Coding Period - Week 8"
categories: jekyll update
toc: true
toc_label: Table of Content
sidebar:
  nav: "docs"
---
With the Exercise details list sheet, It was easy to plan ahead on how to migrate the remaining exercises into React.

### Goals

- [x] 3D reconstruction Exercise

- [x] Vacuum cleaner Exercise

### Accomplishment and Challenges 

* #### 3D reconstruction Exercise \[Task 1\]
Three, OrbitControls, OBJLoader, Colladloader, 3d_scene, 3dviz, pose3d - Started with the Three JS Widget and completed the exercise specific Script files.
Javascript files like Three, OrbitControls, OBJLoader, ColladLoaders were present in the three.js library, so they were imported directly.Lets examine the remaining three separately.

1. *3d_scene* - This Javascript file was responsible for creating the scene, camera, renderer and adding the light to the scene. It also had the function to render the scene.

2. *3dviz* - This Javascript file contained the initialization method such as init() and setting the configurations for server, port, updatePoints, updateSegments, linewidth, pointsize, spheresize, camera and camera position.

3. *pose3d* - This Javascript file contained the function getYaw, getRoll and getPitch. These functions were used to get the yaw, roll and pitch of the object.

* #### Vacuum cleaner Exercise \[Task 2\]
With the help of the Exercise details list, Follow line exercise matched with the vacuum cleaner exercise. The main purpose of using react was to make reusable widgets to easily migrate the remaining exercises. Now, the widgets created so far were put to test whether they can be reused or not, Corresponding changes were made to the widgets that were unable to be reused. Making the widgets more powerful and reusable. 


<img src="{{ site.url }}{{ site.baseurl }}/assets/images/vacuum_cleaner.png" alt="" class="full">


### Issues and Pull Requests

* #### Issues

  - [ \[ VacuumCleaner \] Migrate Vacuum-cleaner exercise to use a REACT based frontend ](https://github.com/JdeRobot/RoboticsAcademy/issues/1809)

  - [ \[ 3DReconstruction \] Documentation on react widgets](https://github.com/JdeRobot/RoboticsAcademy/issues/1810)

* #### Pull Request

  - [ \[Exercise \] React Based Exercise ](https://github.com/JdeRobot/RoboticsAcademy/pull/1805)

### Achievements

🎉🎊🙌🏻 3D Reconstruction and Vacuum cleaner Exercise Completely migrated and working perfectly. 🎉🎊🙌🏻 

<!-- * Exercise - [Follow Line React](https://youtu.be/YMMQVo_3oh8)

<iframe width="420" height="315" src="http://www.youtube.com/embed/YMMQVo_3oh8" frameborder="0" allowfullscreen></iframe> -->
