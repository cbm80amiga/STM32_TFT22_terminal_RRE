
# Minimalistic STM32 and ILI9431 based terminal

Code for the videos:

https://www.youtube.com/watch?v=OgaLXoLhz4g

https://www.youtube.com/watch?v=DAAbDGCeQ1o

# Connections
 STM32 SPI1 pins:
 
  PA4 CS1
  
  PA5 SCK1
  
  PA6 MISO1
  
  PA7 MOSI1
  
  PA11 RST
  
  PA12 DC
  
  
TFT2.2 ILI9341 from top left:

  MISO  PA6
  
  LED   +3.3V
  
  SCK   PA5
  
  MOSI  PA7
  
  DC    PA12
  
  RST   PA11 or +3V3
  
  CS    PA4
  
  GND   GND
  
  VCC   +3.3V
  
# Programming STM32 via serial
Tools/Board set to Generic STM32F103C

Tools/Upload set to Serial

Top jumper set to 1, press reset button before uploading

# Serial adapter to STM32
  PA9 /TX to PC RX
  
  PA10/RX to PC TX
  
  3V3 (don't use 5V!)
  
  GND
  
# Fonter
Improved font conversion tool by CNLohr can be taked from my fork of his pylotron game
