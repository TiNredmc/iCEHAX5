# iCEHAX5 FPGA 

iCEHAX5 FPGA is a bare-minimum and open-source FPGA development board based on iCE5LP1K, iCE5LP2K, or iCE5LP4K. With the help of the iCEBlaster. Drag-and-Drop programming made it easy. Compatible with Windows, Mac OS and Linux without any additional drivers. 

# iCEHAX5 Hardware Specifications 
- iCE5LP1K or iCE5LP2K or iCE5LP4K (QFN48 package; -SG48).
    - 1100 or 2048 or 3520 Programmable Logic Cells (PLBs).
    - 64 or 80 or 80 kBit Block RAM (BRAM). 
    - Single programmable Phase Lock Loop (PLL).
    - 2 or 4 or 4 Multiplier And Accumulator DSP blocks (MAC).
    - 1 or 2 or 2 I2C Hard IPs.
    - 1 or 2 or 2 SPI Hard IPs.
    - 10Khz and 48MHz internal Oscillator 
- 37 Usable Pins
    - 34 User accessible PIOs
    - 3 Open Drain Only pins for RGB LED.
- iCEBlaster USB Drag and Drop programmer.
    - Based on STM32F042F4P6 or STM32F042F6P6.
    - Bitstream storage : BR24G1MFJ 128kByte I2C EEPROM (I know it sucks, but it work!).
    - Bitstream transfer to the FPGA over SPI bus 
- On board LED status for iCEBlaster.