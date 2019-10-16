# TIMER A Blink
Using the built-in timers TIMER0 and TIMER1, this program blinks both LEDs simultaneously.

# BOARDS USED
MSP430G2553
MSP430FR6989

On the G2 board, TIMER0 counts down from 50000 and blinks LED P1.0 while TIMER1 counts down from 65000 and blinks LED P1.6. On the 6989 board, TIMER0 counts down from 50000 and blinks LED P1.0 while TIMER1 counts down from 60000 and blinks LED P9.7.