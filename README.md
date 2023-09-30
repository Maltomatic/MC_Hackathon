# MC_Hackathon
A smart garden hub implemented on an STM32 board.

## Features
* Auto bug spray
  
An ML algorithm assesses current temperature, humidity, brightness etc. to determine plausible density of cabbage worms, then adjusts amount of spray to squirt accordingly. Sensor data gathered by various sensors; spray control by PWM + timer on water pump motor.
* Optimial conditions
  
Avoid over-watering; fertilizer/water/light control optimized based on environmental conditions
* Sleep control

Sleep and wake on a timer because you don't need to water the plants all day long, do you?
* Extensible platform

Multiple of such devices can communicate with one another to control the same garden, or with different parameters for different species
* WIP - default plant species selection

To hardcode optimal watering/fertilizing/lighting parameters for different common species for ease of setup. More gardening know-how required.
