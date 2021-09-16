# the entire project is based on three activities 
# three actvities are interrelated 
## FLOW CHART
![flowchart](https://user-images.githubusercontent.com/89764663/133644702-ec93c991-544b-42fb-aa90-78d568901f06.jpg)
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

