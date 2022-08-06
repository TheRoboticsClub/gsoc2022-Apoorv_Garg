---
layout: single
permalink : /midEval/
title:  "Mid term Evaluation"
categories: jekyll update
sidebar:
  nav: "docs"
---
Mid term Evaluation, an interesting phase that comes up in the gsoc period, I was very nervous and worried about the result as I was stuck on the very first exercise. The exercise though completely refractored but wasn't loading the code in the correct way, Discussed the issues with my mentors, they described me the way to approach this solution, explained the previous workflow and asked to check whether the current workflow follows the same or not.

### Goals

- [ ] Slicing problem of the ace editor code in "brain.py" 

- [x] Frequency Menu Widget 
 

### Accomplishment and Challenges 

* #### Slicing Problem of the ace editor code in "Brain.py"   \[Task 1\]

Now with all the widgets and functionalities complete, I was testing the exercise to make sure everything is complete and ready to deploy for the general users. When I tried loading the code into the robot, the code sent to the manager first and gets evaluated via Pylint and after passing the test it goes to the exercise.py via websocket_code from where the code is sent to the Brain.py , where we are getting the issue !.

* #### Frequency Menu \[Task 2\]

This Menu displays the actual brain frequency, gui frequency and simulation real time factor coming from the backend.
