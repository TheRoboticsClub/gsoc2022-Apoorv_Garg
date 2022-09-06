---
layout: single
permalink : /CPW4/
title:  "Coding Period - Week 4"
categories: jekyll update
toc: true
toc_label: Table of Content
sidebar:
  nav: "docs"
---
All the components for follow_line exercise were migrated to react based code. Now for this week, All the functionalities have to be migrated to react so that components can communicate with each other and also connection with the manager \( brain \) has to be done.

### Goals

- [x] Remove depreciated and old Vanilla Javascript Files

- [x] Ace Editor component error resolved

- [x] Scripts to be migrated to React 

### Accomplishment and Challenges 

* #### Remove depreciated and old files \[Task 1\]

When I first started migrating the exercise's functionalities from Vanilla Javascript to React based, I migrated the Javascript files present in the file path \( from repository root \) "exercises/static/exercises/exercise-id/web-template/assets" which were old and depreciated JS files which I realised when I tried testing the code and got problem in the variable "radiConect". I discussed the problem in the weekly meet and also posted my query on the community slack channel. When I discovered what the problem was, I raised an [issue](https://github.com/JdeRobot/RoboticsAcademy/issues/1770) in Github platform and also created a [Pull Request](https://github.com/JdeRobot/RoboticsAcademy/pull/1771) to solve the same.

* #### Add Ace-build scripts file \[Task 2\]

Whenever we try to load the ace editor component, many warnings were thrown which was not letting us load the theme and language mode in Ace editor.The reason of warnings were it was unable to load "theme-dracula" and "mode-python" files.It was not also allowing us to set the options like enableBasicAutocompletion, enableLiveAutocompletion, and enableSnippets. To resolve this issue, I added the Ace-builds files in that static folder and imported those files in the Ace Editor component.

```
import '/static/common/ace-builds/src-noconflict/ext-language_tools';
import '/static/common/ace-builds/src-noconflict/mode-python';
import '/static/common/ace-builds/src-noconflict/theme-dracula';
import '/static/common/ace-builds/src-noconflict/snippets/python';
```

* #### Migrate common Scripts \[Task 3\]

1. utils.js
2. setIframe.js
3. ws_code_teleop.js
4. local_functions.js
5. websocket_address.js


* #### Migrate exercise specific Scripts \[Task 4\]

1. circuit_selector.js
2. controller.js
3. ws_gui.js
4. birds_eye.js
5. launcher.js

* #### Migrate scripts present in exercise.html \( Follow line \) \[Task 5\]

1. ConnectionUpdate
2. enableSimControls
3. enablePlayPause
4. togglePlayPause
5. toggleResetButton
6. toggleSubmitButton
7. changegzweb
8. changeconsole

* #### Migrate scripts present in exercise_base.html \[Task 6\]

1. onPageload function
2. beforeUnLoad function
3. handling different event listeners


### Pull Request and Issues

* #### Issues

1. [https://github.com/JdeRobot/RoboticsAcademy/issues/1770](https://github.com/JdeRobot/RoboticsAcademy/issues/1770)

2. [https://github.com/JdeRobot/RoboticsAcademy/issues/1671](https://github.com/JdeRobot/RoboticsAcademy/issues/1671)

* #### Pull Requests

1. [https://github.com/JdeRobot/RoboticsAcademy/pull/1771](https://github.com/JdeRobot/RoboticsAcademy/pull/1771)

