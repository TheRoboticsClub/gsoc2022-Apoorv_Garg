---
layout: single
permalink : /CPW3/
title:  "Coding Period - Week 3"
categories: jekyll update
toc: true
toc_label: Table of Content
sidebar:
  nav: "docs"
---
In the weekly meet, I showed the mentors the so far developed exercise base and discussed about the obstacle I was stuck at and discussed about the next week agenda (mentioned in the Goals).


### Goals

- [x] Create Bird eye view Widget for the follow line

- [x] Circuit selector

- [x] Setup the Gazebo viewer

- [x] Setup the Console viewer

### Accomplishment and Challenges 


* #### Create Bird eye view Widget for the follow line exercise \[Task 1\]

There is a viusalization section in the follow line exercise which have a bird-eye view for the circuit. This component is a canvas where we load the background image as different circuit whose value depends upon the circuit selector component. Now, the purpose of canvas was not just to load the circuit image but to render a robot(Red Circle) also and when someone loads the code into the robot from the ace editor, the red circle will changes its position accordingly to the code loaded.
To migrate this component from vanilla javscript to React, two challenges that I faced was -
1. Loading Code into robot - I have been trying to connect with the websockets and for that I was migrating the javascript content present in the assets folder present in the exercise but that folder content was old and depreciated. Later, In the meet and through slack channel of Robotics academy, I was able to identify the error and fix the bugs.
2. State Management - Managing all the states were getting a bit tricky. To deal with it , I read about two state managemnt tricks - One was **Redux** and other was **context**.


| Redux | Context | 
|-------|--------|
| Additional installation Required, driving up the final bundle size | Built-in tool that ships with React |
| Requires extensive setup to integrate it with a React Application | Requires minimal Setup |
| Works like a charm with both static and dynamic data | Specifically designed for static data, that is not often refreshed or update |
| Easily extendible due to the ease of adding new data/actions after the initial setup | Adding new contexts requires creation from scratch |
| Better code organization with separate UI logic and State Management Logic | UI logic and State Management Logic are in the same component |


* #### Circuit Selector \[Task 2\]

This component is basically a dropdown menu, that consists of different type of circuits offered by the exercise -

1. Default Line
2. Montmelo Line
3. Montreal Line
4. Nürburgring Line

On changing the value of circuit, a new track is loaded in the canvas.

* #### noVNC Gazebo \[Task 3\]

To recreate the Gazebo Simulation, react-vnc library was used. It takes the launch files from the static content present in the exercise. iframe are bascially used at the core to render the Gazebo. An url is passed to the VNC Gazebo that connects the simulation completely.

* #### noVNC Console \[Task 4\]

To recreate the Console Simulation, react-vnc library was used. iframe are bascially used at the core to render the Console. An url is passed to the VNC Console that connects the console completely.


