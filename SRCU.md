[Home](index.md)

## Goals and Focus 

To create a open source pneumatic control unit that runs on an ATtiny85 that can pump and control flow and pressure into a soft robot.
## Outputs

## Progress Log

===================

(7/21/2018)
While I am waiting for some parts to come in the following is pictures of the orginal design using a peristaltic pump and a motor speed and direction controler(assembled circuit from amazon esentially just an H bidge and some pwm control).

![Old Design 1](https://i.imgur.com/WrXzpnN.jpg)

![Old Design 2](https://i.imgur.com/XvWX0XC.jpg)


---------------------------------------------

(9/11/2018)

Here is a long overdue update on this project:

I have acquired a few ATtINY boards and am quite satisfied with the performance. To run the motors I originally bought a couple of small dual h bridge breakout boards, these are fairly standard and simple to control with an integrated example code in both the aurdino IDE and the included ATtiny examples from uploading the firmware. However after trying to run the program it seemed that the motor tried to turn but ultimately failed, looking at the current ratings for the output of the H Bridge and the no load current of the motor it was apparent that I would need a higher current H-Bridge if I was to try this. I bought a 30Amp controller that was overkill a while back and decided to try it. The control scheme wasn't clear but I tried a similar one to the other h Bridge. This time it worked and the motor started turning, but the ATtiny started to over heat and the motor would stop and start again. I am not sure if I hooked up everything right and am going to the hacker space tomorrow to see if I can get insight. 

(7/17/2018)

I am starting off with a unit that I have used that uses a peristaltic pump and a motor speed control unit. I want to instead use a diaphramgm pump and an h bridge unit run by an ATtiny. The diaphram pump promisies more pressure then can be acheived by a perastatic motor, the problem being that these motors are rather expensive, however searching ebay I found ..... that seems promising. 
