---
layout: single
permalink : /CPW6/
title:  "Coding Period - Week 6"
categories: jekyll update
toc: true
toc_label: Table of Content
sidebar:
  nav: "docs"
---
It was the time to show the demo to the mentors, when I started with the demo, Things didn't run in the manner they should have, so mentor told me *It's called the demo effect - "The fact of device working perfectly always except when demonstrated for an audience."*  Then we figured out some problems that were required to solve at the earliest. 

### Goals

- [x] Calculate the initial position of the Robot dynamically 

- [x] Connection with the manager was not persistent due to initialization inside Context
 

### Accomplishment and Challenges 

* #### Robot position initialization  \[Task 1\]

The red circle that is drawn on the bird view widget was not coming to its correct position, it needed to be align with respect to the size of widget.
To solve the problem, we will use the phaser library to make the bird eye view more powerful.

* #### Persistent connection with the manager \[Task 2\]

Major problem that I am facing was to keep a persistent connection with the manager. The reason of the failure was improper definition of the websocket, I defined the websocket inside the Context, so whenever the context was getting re-render, a new socket connection was made *for 2.7k times*. So I had to come up with a different approach to define the websocket that I don't lose the data and also doesn't make a connection again and again.
To solve the problem of persistent connection, I had to define the variable globally.
