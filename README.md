# Timer3-Output-Compare-STM32F411RE
This program is to use ITM3 output channels 1,2,3 and 4 in the Output Capture Mode. This, to generate 500, 1000, 2000 and 4000 Hz signals. 
The way to check that is working, is using an oscillocope and coneecting it to the respective pins of Timer 3 channels. 
The other way is adding Timer3-Input-Capture-USART2 project and using a wire between the pins, then, send the frequency signal to Teraterm using USART2
