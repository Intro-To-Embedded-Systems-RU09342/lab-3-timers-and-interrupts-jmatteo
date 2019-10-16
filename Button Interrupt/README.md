# Button Interrupt
These programs use the following code in order to use hardware interrupts inside the MSP430

```c
#pragma vector=PORT1_VECTOR
__interrupt void Port_1(void)
{
}
```

# Boards Used:
MSP430G2553
MSP430FR6989

The program for the MSP430G2553 uses the interrupt to toggle the state of the LED P1.0 whenever the button P1.3 is pressed. The program for the MSP430FR6989 uses the interrupt to activate the LED P1.0 whenever the button P1.1 is pressed and deactivate when the button is released.
