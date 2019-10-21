## Lecture 4

## tldr 
Need to know the bits and resolution. Need to sample as 2 x as max frequency.

## Analogue input
12 bit conversion rate of 200kHz 
- Do not use AD7 and AD8
- 3v range

#### Do not use pin 18 immediatly as it can also be used as a analogue output
## Analogue output 
#### Below uses a resistor laddar and uses a op-amp to get a specfic voltage
Analogue output
10 bit digital to analogue convertor
Buffered output
1 Mhz update freq

#### NB PWM crude digital-analogue

### Need to create a graph for the 10 bit convertor.
#### If time do a map

Steps

1) Configure pin (multiplexer)
   1) 
2) Dac init
3) Dac update value

## DAC_Init()
### Dac_updatevalue



## PWM to analogue
1) Have a RC filter
2) It needs to be large enough to remove ripples but trade if too large slow to change due to inductance

## Dual edge vs single edge mode
Use registers if driver functions don't work.

