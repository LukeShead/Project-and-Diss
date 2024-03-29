# Project-and-Diss
Project and Dissertation for my MSc, Chat-bot with visual representation for student well-being. Will utilise Google Voice API, Android development, TensorFlow use in order to design an application for the BlueFrog Robotics Buddy Pro robot model. 
[Webpage for Buddy Pro](https://www.bluefrogrobotics.com/robot/)

This Project will be for my MSc in Artificial intelligence that I am attending in the University of Kent. The project started in January and will continue through to september, where my project and dissertation will be due.

To start my research into creating and understaning the process of development, I am reading the paper and critiquing: https://ieeexplore.ieee.org/abstract/document/7919664?casa_token=8elvD97S5zsAAAAA:N6wCb_6Lf8XKpc44-ZXuimOETW92j82ugQI5ZfY72esk9311aN5xUOZqYHtjIpTKmrIHiPw

## Buddy SDK and development tools

### TensorFlow (optional)

Open source Machine Learning library that handles many functions for creating and calculating the neural network being able to handle the internal hidden layers, this will be used to help the AI chatbot learn and allows streamlining of the functions that might take up more time.

### Android Studio

Folder: res/layout
XML files that describe the
layout of the UI of the
application.
These could be:
• Layout files for each activity.
• Layout files used for
dynamically adapting the
User Interface.


AndroidManifest.xml
XML file with general
declarations about your
application, e.g.:
• Which version of Android it
runs on.
• What security permissions
it requires.
• What activities or services it
consists of
Declares components
• Names required libraries
• Lists permissions required
• Associates components with intents
• Says how each intent should be invoked (e.g. by
the Launcher)
• Specifies icons and labels for display to the user




### Buddy Pro SDK



### Android Debug Bridge

The connection between the OS and the Buddy pro is handled through ADB in android studio. The server will be set up in the testing area and will be run on the same device as the client. The Buddy pro will be the Daemon (adbd) in this scenario.

#### quick code test

```Python
a = "Hello World!"
print("a")
```


## Project Plan (rough at the moment)

### June:
Research into Buddy Pro SDK,
Learn Android Studio,
Research and learn TensorFlow functions to support the learning process,
Resarch how to integrate the Buddy Pro SDK into the project for robot functionality.
Keep Github updated

### July:
Have Android studio app functional by middle of July (potentially have robot already talking)
Have the Robot running correctly and fully functioning by the end of the month
Keep Github updated
Keep meetups with supervisor

July 7th:
First visit to the robotics lab,
Getting familiar with the Buddy's functions and software
Plan for next: Start creation of android app at a base level before coming back into the lab.

App notes:

Must run on Android 9.0 (made a mistake on that already).
Runs through Java not Kotlin.
Follow User guide in order to set up the app. 
Will not be able to test unless the lab is visited.

### August:
Plan the structure of the dissertation,
Start Dissertation using sources from Github,
Be finished before the end of the month.
Keep Github updated
Keep meetups with supervisor

## Project Design

### Objectives for the project.

Robot will be able to start a conversation with a student

Robot will be able to follow conversations with a student

Robot will be able to use personal insights in a conversation.

Robot able to recognise signs of unhealthy wellbeing.

Robot able to offer support and directions for professional help.

Conduct experiements with different students for testing.

### Features for the project.

Buddy robot capable of Facial recognition to preregistered faces.

Creation and completion of an original android app made from scratch

Robot will personalise people based off stuff like favourite food, place, hobbies. 
e.g. Favourite food being banana, robot will recognise that and use it conversations

(optional) Emotion Recognition with the use of TensorFlow.

(optional) Full environmental navigation.


### Setting up the project

To get started with the project I first had to get comfortable with Android Studio, since the BuddyPro uses an android tablet as it's face, using Android Studio in order to create the application would give me a variety of benefits, including built in wi-fi connection and testing with Android Debug Bridge, as well as a visually being able to code with drag and drop features with elements such as the buttons, images or widgets. Which proved extremely useful during.

The first issues I encountered were trying to set up the BUDDYPRO SDK, following the instructions only took me so far, as some of the functions were in pre-built packages, not included in the sdk. This meant that I was unable to interact with the buddypro's functions such as Steering, Facial Expressions and head movement as a base. Eventually I was able to solve this problem by taking an example provided by the BuddyPro team, and building upon it in order to incorporate my own functions and the Speech API.


### Troubles with BrainShop API

One of the first API's I tried was BrainShop, as after looking into some good chatbot API's for Android most websites recommended it, I failed to look into how it allows developers to interact with the API. In Februrary of 2022 they announced that the API would only be available for any 3rd parties, I originally planned to use Google's API but thought using a more specialised version for android would be better, howevever deviating from that plan only caused more issues for myself. In the future I would do more research into a new API, or be more resolute with the original plan.
