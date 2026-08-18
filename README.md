# Assistive-Robotics-Camp
This workshop is a part of the Blugold Biomedical Exploration Camp designed to introduce assistive robotics to high school students.

## [Part 1](Part 1):
First, we will perform activities designed to develop basic robotics skills, including applications of electronics and programming. We will use a Raspberry Pi Pico to control a small servo motor using the MicroPython programming language.<br>

The following materials are required:

1. Raspberry Pi Pico
1. Tower Pro 9g servo motor (or another small servo motor)
1. Push button
1. Jumper wires

Instructions for setting up the Raspberry Pi Pico and programming it using MicroPython can be found at: https://projects.raspberrypi.org/en/projects/getting-started-with-the-pico

### Notes: 
[Assistive_Robotics_P1.pptx]()

### [Code](Part 1/Code): 
1. Blink_onboard_LED.py : Blink the onboard LED at regular intervals
1. Blink_LED_button.py : Blink the onboard LED at the press of a button
1. Simple_servo_control.py : Use the Raspberry Pi Pico to control the servo motor by moving it between two designated positions at regular intervals. Can you change these designated positions?
1. Button_servo_control.py : Use the Raspberry Pi Pico to control the servo motor so that it moves to a designated position when the button is pressed and returns to its original position when the button is released.

## [Part 2](Part 2):
Next, we will apply what we have learnt in Part 1 onto a scale sizxe elbow exoskeleton. The activation signal here will be your muscle instead of a push button. <br>
The following materials are required:
1. Raspberry Pi Pico
2. Jumper wires
3. MYOWARE 2.0 Muscle Sensor
4. Motor
5. 3D printed components (.stl files in the [CAD folder](Part 2/CAD))

### Notes:
[Assistive_Robotics_P2.pptx]()

### [Code](Part 2/Code):
1. Blink_LED_EMG.py : Blink the onboard LED using your muscle activation from the MYOWARE sensor
1. Blink_LED_EMG_filtered.py : Blink the onboard LED using a filtered muscle activation from the MYOWARE sensor
1. Exoskeleton_EMG_Servo.py : Use a filtered muscle activation from the MYOWARE sensor to control the servo motor so that it moves to a designated position when the muscle is activated 
