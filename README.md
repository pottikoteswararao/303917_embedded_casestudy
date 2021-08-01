# EMBEDDED CASE STUDY
## Requirements
![activity](https://user-images.githubusercontent.com/86213638/127768471-4c145bf5-e2ad-410a-a46e-4df37201f181.PNG)
### Above diagram represents case study and requirements
* Button Sensor will check the passenger is sited or not
* Heater will check the heater button is ON.
* Temp to CAN shows the value of temperature gone over protocol
## Temperature values of heater
Temperature values depends on ADC values and gives output PWM values in CRO
| ADC value(Temperature sensor) | Output PWM |
| --- | --- |
| 0 - 200 | 20% - `20°C` |
| 210 - 500 | 40% - `25°C` |
| 510 - 700 | 70% - `29°C` |
| 710 - 1024 | 95% - `33°C` |
