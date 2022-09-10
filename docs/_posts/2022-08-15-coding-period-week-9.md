---
layout: single
permalink : /CPW9/
title:  "Coding Period - Week 9"
categories: jekyll update
toc: true
toc_label: Table of Content
sidebar:
  nav: "docs"
---
Robotics academy has 5 categories of exercises, namely, Autonomous Driving, Service Robots, Drones, Computer Vision and Industrial Robots. With the completion of follow line, 3d reconstruction and vacuum cleaner exercise, 
we were done with autonomous driving, computer vision and service robots respectively. So, we decided to go ahead with one of the remaining category i.e. **Drone**. For the purpose of drone exercise, I was adviced to have talk with [pariaspe](https://github.com/pariaspe) and get the details of the drone exercise. After having a discussion with pariaspe, I took the rescue people and power tower inspection exercise as the next challenge

### Goals

- [x] Rescue people Exercise

- [x] Power tower inspection Exercise

### Accomplishment and Challenges

* #### Rescue people Exercise \[Task 1\]

Rescue people exercise is the best fit to start the migration of Drone exercise. Rationales for saying its' the best fit is - It utilizes all the common functionalities. So this exercise can be easily set as a base for other drone exercise.

One interesting challenge that I faced while migrating was, It uses two gui_canvas, now I had to reuse the same widget in a single view without replicating the code. To resolve that I added a prop named as drone \( boolean type \) which lets you set the *ref* and *id* of the canvas. 

* #### Power tower inspection Exercise \[Task 2\]

Since rescue people exercise was completely migrated, It took only a few minutes to migrate this exercise to react. Only a Single change in context was made, the view remained the same. In the template only necessary changes were made.

### Issues and Pull Requests

* #### Issues

- [ \[ RescuePeople \] Migrate Rescue-People exercise to use a REACT based frontend ](https://github.com/JdeRobot/RoboticsAcademy/issues/1811)

- [ \[PowerTowerInspection \] Migrate Power-Tower-Inspection exercise to use a REACT based frontend](https://github.com/JdeRobot/RoboticsAcademy/issues/1813)

* #### Pull Request

- [ \[Exercise \] React Based Exercise ](https://github.com/JdeRobot/RoboticsAcademy/pull/1805)

### Achievements

🎉🎊🙌🏻 Rescue people and Power tower inspection Exercise Completely migrated and working perfectly. 🎉🎊🙌🏻 

<!-- * Exercise - [Rescue people React](https://youtu.be/YMMQVo_3oh8)

<iframe width="420" height="315" src="http://www.youtube.com/embed/YMMQVo_3oh8" frameborder="0" allowfullscreen></iframe> -->

<!-- * Exercise - [Power tower inspection React](https://youtu.be/YMMQVo_3oh8)

<iframe width="420" height="315" src="http://www.youtube.com/embed/YMMQVo_3oh8" frameborder="0" allowfullscreen></iframe> -->
