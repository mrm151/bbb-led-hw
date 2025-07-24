# BBBLedHW
Hardware for the beaglebone black --> stm32 --> LED light strip project

## Subsystems
* STM32 Serial Wire Debug
* LED Light Strip
* Main Power
* STM32 power
* RF network
* USB Power


Do I want the option to just power the MCU and not the LEDs? Probably
How would I do that?

Have a 5V USB-B Micro or USBC connector which bypasses the 5V regulator and goes straight into the 3V3 regulator for the MCU

Could disable the 5V regulator when USB is plugged in - do this via the enable pin


