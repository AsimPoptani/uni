## Timers
Has a total of 8 timers
 - Watch dog timer 
   - This is for safety critical application. Used to set the system to go into a state
   - Set watchdog to shutdown into a safe state
   - The watchdogtimer needs to be reset so it does not trigger.
  - Set WDTC register for a constant e.g. 400ms
  - Set WDMOD - WDEN (watchdog enable) and WDRESET (reset the timer)
  - WDFEED give 0xAA 0x55 to enable to the Watchdog
  - WDT_IQRhandler is the interupt

- Real time clock
  - Has a ss/mm/hh dd/mm/yy 
  - Handler RTC_IQRHandler
  - Ultra low powered 
  - has interupts

RIT - Reptitive Interrupt Timer
- More powerful than SYSTick
- You have a mask and a match value
- General timers X4
  - Count external pulses
  - Two 32 bit capture channels 
  - 