# Temperature-measurement-with-LM35---STM32F407
Reading LM35 with ADC, UART communication with computer

Temperature is measured with LM35 and this information is transferred to the computer via UART communication. 

## Microprocessor pin settings:

- A port pin 0 : ADC for LM35 

- A port pin 2  : Rx pin for UART.  

- A port pin 3  : Tx pin for UART.  

## Pinout diagrams :

### FT232RL Module:

<img src="https://github.com/CakirBrs/Temperature-measurement-with-LM35---STM32F407/blob/main/Assets/uart.png" width="256" title="FT232RL Module pinout diagram">

### LM35:
<img src="https://github.com/CakirBrs/Temperature-measurement-with-LM35---STM32F407/blob/main/Assets/lm35.png" width="256" title="LM35 pinout diagram">

#
The value read with A0 pin is converted to celcius degree and transferred to the computer via UART. 

###PuTTY

![uart_lm35](https://user-images.githubusercontent.com/26774013/218888540-cbd33ce2-6181-4e0d-af8f-bf9cca582e34.gif)

### Circuit

<img src="https://github.com/CakirBrs/Temperature-measurement-with-LM35---STM32F407/blob/main/Assets/lm35diagram.png" width="512"/>

<img src="https://github.com/CakirBrs/Temperature-measurement-with-LM35---STM32F407/blob/main/Assets/lm35breadboard.jpg" width="512"/>



