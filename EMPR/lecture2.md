## Project info
- Using LPC1768
  - ARM Cortex M3 core
  - Harvard arch
  - 100 mhz clock
  - 64kb RAM
  - 512 Kb flash storage
  - Nested IC
  - 32 bit processor
  - Built for real time
  - ethernet 
  - DMA 
  - CAN Bus
  - 3 I2C controllers
  - SPI controllers
  - USB
  - UART x 4

## Mbed arch
- Write to a UART to print


## FYI / advice
- When making the project at then end use a digital diagram of the whole circuit.
- Only use `gcc` for conmpatiblity issues
- Setup then run
- **Do not overcomplecate it use the DMA when got MVP**

### Makefile
There is a supplied makefile 

Top segment is a **do not touch**

The bottom segment is a **do touch** see lecture 2 

### SysTick timer

`SysTick_Handler` ISR can service as a simple timer smallest timer of `10ms` it also has a interrupt of `STCLK` 


### Mini Projects
#### Led Buster
Write a program that switches on LEDs for about 1 second and which loops 5 times.

## TODO 
- [ ] create some libs for ourselves
- 