# INTRODUCTION
## THE CONCEPT OF HEATED SEATS IS ADOPTED BY ALMOST EVERY LATEST MODELS BY ALL AUTOMOBILE COMPANY THESE DAYS LIKE TOYOTA,HONDA,KIA,ETC.THE COMPANY IS OFFERING HEATED SEATS IN THE CARS TO PROVIDE COMFORT AS IN SOME PLACES TEMPERATURE ARE LOW AND THE DASHBOARD CENTRALIZED AC IS NOT CAPABLE TO MAINTAIN PROPER TEMPERATURE IN CABIN.KEEPING THIS IDEA A PROTOTYPE MODULE IS IMPLEMENTED IN THIS PROJECT.
# OBJECTIVES
## TO PROVIDE COMFORTABLE REQUIRED TEMPERATURE BY WARMING THE SEAT
# HARDWARE REQUIREMENTS
## ATMEGA 328 MICROCONTROLLER
## BUTTON SENSORS
## TEMPERATURE SENSORS
## HEATER
##  LED 
## LCD 16*2
# Product Features
## FMVSS 302 flammability compliant

## 9” x 19” heating elements included

## Three element trimming locations

## Insulation protects wires from damage

## Latching wire harness connectors

## High-temp rated element adhesive

## FLOW CHART
![flowchart](https://user-images.githubusercontent.com/89764663/133644702-ec93c991-544b-42fb-aa90-78d568901f06.jpg)
# SWOT Analysis- Strengths, Weakness, and Oppurtunities
# Strengths
## 1.Low cost

## 2.Modular Based programs

## 3.Easy to Modify the Temperature Values

## 4.User Friendly

# Weakness
## 1.It"s only applicable for the countries which having lowest temperature
# Oppurtunities
## 1.It can be implemented by replacing hereby air conditioners so that it will help in all countries

# 4W's and 1'H
## 4W's
## 1.What: Passenger seat and heat monitoring system

## 2.Where: Used in Automotive industry

## 3.When: At low Temperature

## 4.Why: For being healthy
# 1'H
## 1.Operates by modifying the temperature
#REQUIREMENTS
## HIGH LEVEL REQUIREMENTS
|ID |DESCRIPTION
|-- |-- |
|HLR_1 |BUTTON SENSOR WILL CHECK THE PASSENGER IS SEATED OR NOT
|HLR_2 |TEMPERATURE SENSOR AS PER MENTIONED
|HLR_3 |DISPLAY CDD-CRO WILL GIVE THE TEMPERATURE VALUE BY SHOWING PWM
|HLR_4 |LED ACTUATOR SHOWS THE DRIVER IS SEATED
## LOW LEVEL REQUIREMENTS
|ID |HLR |ADC-VALUE |TEMP
|-- |-- |-- |-- |
|LLR_1 |HLR_2 |0-200 |20 °C
|LLR_2 |HLR_2 |210-500 |25 °C
|LLR_3 |HLR_2 |510-700 |29 °C
|LLR_4 |HLR_2 |710-1024 |33 °C
## DESCRIPTION
# The temperature sensor will work only when the particular person is seated 
# to detect the person is seated or not the button sensor will come into the picture
# after the button sensor will detect that person is seated on the seat then temperature sensor will sense the temperature 
# led actuator will show the driver is seated

