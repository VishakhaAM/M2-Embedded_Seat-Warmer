## Introduction

The concept of heated seats is adopted by almost every automobile company these days and in every latest model of Toyota, Honda, KIA, etc, the company is offering heated seats in the cars. Most of the companies provide heated as well as cold seats in their models that make the driving experience very comfortable especially in summers. The circuit that I will design later on in this article will be responsible for heating every type of sofa whether it be round arm sofa, square arm, hard wedge, etc. The circuit will be placed at the lower side of the sofa and the seats will automatically start heating after some time intervals. 


## Features
- The System will sense is  passenger seated or not.
-  Passenger has the access to modify the speed of a fan in the bus.
- Low cost and robust system.
- Modular Approach.

## Folder Structure
|Folder             | Description |
|-------------------| -----------------------------------------|
| `1_Requirements`   | Documents detailing requirements and research|
| `2_Design`         | Documents specifying design details|
| `3_Implementation` | All code and documentation|
| `4_TestplanAnd Output`      | Documents with test plans and procedures

## SWOT- Strengths, and Weakness, Opportunities Threats
### Strengths
- User Friendly
- Easy to alter the temperature inside the bus.
- Modular Approach
- Low cost and Robust system.

### Weakness
- Its only applicable for those countries which are having low temperature.
### Opportunities
- It can be implemented by having both Heater and AC.
### Threats
- Not suitable for average or high temperature places.

# 4W's and 1'H
## Who:  
This Device can be used by anyone, It is easy to use .
## What:
The Temperature measurement using atmega328 is capable of maintaining the proper temperature inside the bus what this system will do it will sense the temperature inside the Bus using temperature sensor (LM 35) and it will give the signal to fan which will get switched ONN and Off accourding to requirement  .
## When:
It is made as a part of LTTS Step-in Mini Project work.
## Where:
It's made using Visual Studio Code IDE on Windows 10.
## How:
A simple algorithm is used which has a simple Temperature measurement code and can analyse the input and give the result.

## Detail requirements
### High Level Requirements
| High Level Requirements      | Description |
| ----------- | ----------- |
| HLR1      | Microcontroller   |
| HLR2   | Temperature Sensor|
| HLR3   | Heat Generation|
| HLR4   | Display|
| HLR5   | Software used|

### Low Level Requirements
| Low Level Requirements      | Description |
| ----------- | ----------- |
| HLR1_LLR1      | ATmega328     |
| HLR2_LLR1   | LM35 and ADC|
| HLR2_LLR2   | ADC with PWM-fast|
| HLR3_LLR1   | Thermoelectric module|
| HLR4_LLR1   |LCD and LED|
| HLR5_LLR1   | Code Blocks with AVR GCC compiler |
| HLR5_LLR2   | SimulIDE |
