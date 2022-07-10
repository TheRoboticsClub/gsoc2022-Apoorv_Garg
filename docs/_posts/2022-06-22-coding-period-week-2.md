---
layout: single
permalink : /CPW2/
title:  "Coding Period - Week 2"
categories: jekyll update
toc: true
toc_label: Table of Content
sidebar:
  nav: "docs"
---
In the weekly meet, we decided to start the project with the migration of follow line exercise. Follow line exercise consists of the most basic components.


### Goals

- [x] Creating a Exercise Base React based template 


### Accomplishment and Challenges 


* #### React Based Exercise Base Template \[Task 1\]

To get started with the migration of follow line exercise, I started with the refractoring of exercise_base.html which consisted of the main navigation bar. It consists of functionalities as follow -

First Toolbar - 
1. Connection - This Button connects/indicates the web server with the Robotics Academy Docker Image (RADI).
2. Launch - This button consists of three states - launch, launching and ready.
3. Button Group [ Documentation / Editor mode / Forum ] - This button group provides three functions - documentation, editor mode and visualization of exercise and forum to raise issues and doubts to other fellow developers.

Second Toolbar -
1. Load File - To load a file in ace editor,
2. Save file - To save the current code of Ace edtior,
3. Load in Robot - To load the code in robot,
4. Play - To play the visualization, 
5. Stop - To stop the visualization,
6. View Sim - Opens Gazebo and helps in Simulation task,
7. View Console - Opens Console, 
8. Teleoperate
9. Brain frequency \[Hz\] - Number of iterations of the robot brain,
10. GUI frequency \[Hz\] - speed of the Graphical User Interface code,
11. SIM RTF \[Gazebo simulator's Real Time Factor\] - It indicates how smoothly the simulation is running. The closer you are to 1, the better. For an instance, Consider an RTF = 0.3, it represents 1 wall clock second simulates only 300ms of simulated time.

Main challenges that I faced was how to connect all the react based code to Django templates style. To acheive that I consulted the mentors and asked for their advice.  


