# Hardware Challenge 1
## Goal
Sense the environment in some way of your choice (light, temperature, sound, water level in your plant, etc.) and respond somehow.  Go to @290 for posting your submission.

## Description
In this project, I am familiarizing myself with interacting with the GoPiGo board as well as learning how to use attached sensors.

This project uses a Grove loudness sensor to determine how loud the ambient noise is. 

Every few seconds, the loudness sensor samples the sound level 10k times. After collecting the samples, it determines the average loudness.  The GoPiGo eyes are then used to indicate the relative "safety" of the volume level.

Volume Levels:
- Green - quiet
- Pink - noisy
- Orange - put in your ear plugs
- Red - danger, Will Robinson.

## Demo
[Demonstration Video](https://youtu.be/FjBthg8KJLI)
 
Resources:
- GoPiGo Loudness Sensor - https://gopigo3.readthedocs.io/en/master/api-basic/sensors.html#loudnesssensor
- GoPiGo Eye Color - https://gopigo3.readthedocs.io/en/master/api-basic/easygopigo3.html#easygopigo3.EasyGoPiGo3.set_eye_color
- GoPiGo Port Layout - https://gopigo3.readthedocs.io/en/master/api-basic/structure.html#hardware-ports
- RGB Color Lookup - https://www.colorhexa.com/ffa500

# Hardware Challenge 2
