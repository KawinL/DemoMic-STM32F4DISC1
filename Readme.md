How to use this project 
- Import to System Workbench for STM32
- Bulid all
- Done

Description  
1. The board will send n-number of '|' characters via UART. Where the amount of '|' will corispond to the number of high bit (1) in the sampling data in binary format. Example, if the sampled data recived 1111.0000.1100.1010 (16 bit PDM) the number of high bits is 8, thus the UART output will be "||||||||".  
2. LED will light up if the sound loud enough.

Navigation
- DemoMIC.ioc - pin configuration
- Src/main.c - main file of this project
