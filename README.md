<h1>FIFA 3K19 <sub><sup><sub><sup><sub>A project by #TeamOP</sub></sup></sub></sup></sub> </h1> 

![Completed Project](https://github.com/gunalankarun/FIFA-3K19/blob/master/images/completed.jpg)

## Overview

FIFA 3K19 is a two player foosball simulation created for the Tiva™ C Series TM4C123G LaunchPad by Gunalan Karun and Jason He. It was created as the final project for the EE 319K Embedded Systems class taken at UT Austin in the Spring of 2015 with Dr. Nina Telang.<br/> 

See images folder for pictures and screenshots.

## How to Play

The objective of the game is to score 5 points first. Each player has the ability to control 3 rows of foosball paddles and a button to speed up the ball when it hits the slider (mimicking the kick functionality of a real foosball table when the handle in spun). Players must prevent the ball from entering their respective goals while scoring on the opponent. In addition there are **three modes:**
+ Easy Mode: middle slider controls all rows of foosball paddles. Activated when clicking the Alt button from the title screen. 
+ Normal Mode: each slider is used to control a row of foosball paddles. Activated when clicking the kick button from the title screen.
+ OP Mode: *REDACTED*. Only activates if you are in #TeamOP (or you can just look through the code and figure out how to activate it).

**Controls:**
+ 3 Player1 Sliders - controls foosball paddle movement for player 1 
+ 3 Player2 Sliders - controls foosball paddle movement for plater 2
+ 2 Kick Buttons - used to mimick kick of ball. increases speed of ball when clicked when ball hits foosball paddle.
+ 1 ALT button - button for mode selection

## Usage and Installation

This code is meant to be used on the tm4c only, with a specific configuration of ports to switches, ADC's, DAC, and LCD. See the port initialization sections in the code for specifics (an example picture of our configuration is above. After building the circuit, simply build and flash software with Keil or other software.

**Hardware Components:**
+ 6 Potentiometers
+ 3 Buttons
+ 1 Color LCD
+ 1 Audio Jack (only used in sound version)
+ 3 Breadboards
+ LOTS and LOTS of electric tape

## Authors

<h4>#TeamOP</h4>
**Gunalan Karun** <br/>
http://github.com/gunalankarun
 <br/><br/>
**Jason He**

## Copyright and license

```
The MIT License

Copyright (c) 2015 Gunalan Karun 

```

