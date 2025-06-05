---
title: "SwiftPulse"
author: "Kushagra"
description: "A powerful, complete timer to be used for speed cubing."
created_at: "2025-05-30"
---

# Day 1
I spent today clearly laying out what I want, and the features that need to be present in the timer. Moreover, I decided on the components I want to use.
What I want:
1. Much like a stackmat timer, you need to place your palms on the two pads on the side, stay in that position for a while, then let go. During this time, an LED will be changing colours to display when the user may remove their hands.
2. (Optional) A scramble is generated and shown, on an OLED screen.
3. (Optional) Inspection time is provided, giving warnings at the specified times. The extra time(if any) taken during inspection is noted to calculate a +2 or DNF.
4. The time is kept track of and displayed on the OLED.
5. Both hands must return to the pads in order to end a solve.
6. +2 or DNF is set.
7. This, along with the last 5 solves is saved.
8. (Optional) It is sent to a computer to save it.
9. There are 4 buttons, viz., left, right, select, reset:
10. Reset resets the time on the timer.
11. Left, right and select are used to interface with the timer.
12. The main menu has an option selection and a start solve selection.
13. The options are: Inspection time, Generate scramble, and send to a computer.

## Parts
### Microcontroller
I decided on using an ESP32 since it has bluetooth and wifi capabilities. Moreover, it also has a built in touch sensor, so it will be easier to make the two pads.
### Buttons
Nothing special about them. Just buttons,¯\_(ツ)_/¯
## OLED
I decided to use a 1.3" 128x64 OLED due to its size and cost-efficiency.
## Buzzer
Again, just a buzzer

# Day 2
Mostly spent today learning about what I2C actually is and exploring easyeda.
