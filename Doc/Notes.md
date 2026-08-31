# STM32H750VBT6 : LED toggling using DMA (polling mode)

## #1: Identify the GPIO port which LED is connected.

-> Ans: GPIOC pin 1

## #2: Identify to which bus GPIOC is connected ?

-> Ans: AHB4

## #3: Identify which bus master can talk to AHB4 peripherals ?

-> Ans: We can use both DMA1 and DMA2.
