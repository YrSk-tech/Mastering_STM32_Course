# Mastering_STM32_Course
All completed tasks from Udemy Mastering STM32 microcontrollers course

## EEPROM Emulator

This application demonstrates how to save and read data from the STM32 EEPROM Emulator. It uses a state machine for debugging purposes, allowing the user to verify if three variables have been successfully saved inside the flash memory.

https://github.com/YrSk-tech/STM32_EEPROM_Emulator

## USBhid app

An application with USB human interface device. Main idea is to controll microcontroller with by only use of usb device for that i used ST-Link V2 mini, and USB HID Demonstrator to see active LEDs buttons and potentiometer state and give reports to microcontroller for activation of LEDs

https://github.com/YrSk-tech/STM32_USBhid

## STM32 USART Advanced App

Upgraded version of USART basis App project with added interrupt and callback functions. Also created 2 instances to check received lenghts of test and Idle Debug counter

https://github.com/YrSk-tech/STM32_USART_Advanced

## USART basis App

Simple application for STM32 microcontroller to communicate by uart protocol with Laptop using USB - UART TTL Convertor

https://github.com/YrSk-tech/STM32_USARTbasis

## RTC basis App

Implemented calendar application with Real-time clock. Added back up configuration with use of Backup RTC register, also added D2 LED to show when microcontroller is backing up data

https://github.com/YrSk-tech/STM32_RTCbasis

##ADC App

This application employs an Analog-to-Digital Converter (ADC) to periodically sample data from a potentiometer. Every 300 milliseconds, the ADC converts the analog voltage signal from the potentiometer into a digital value.
To ensure data integrity, the application includes a timeout mechanism. If the ADC fails to complete a conversion within one second, it aborts the current attempt and initiates a new conversion.

https://github.com/YrSk-tech/STM32_ADCbasis

##IWDG App

This application uses an Independent Watchdog (IWDG) to monitor whether the program freezes for more than 1 second. If the program fails to respond within this time, the IWDG triggers a response by turning on LED D2, signaling that the system has encountered an issue.

https://github.com/YrSk-tech/STM32_TIMbasis

## STM32 TIM Basic - Timer Period Elapsed Interruption Application

This project shows how to use a basic timer (TIM3) in an STM32 microcontroller to trigger period elapsed interrupts.

LED D2: The timer toggles LED D2 every second.
Button Control: Press button BTN_K0 to stop the timer interrupt.
LED D3: A blink pattern for LED D3 is implemented in the Timer 3 callback function as a visual indicator controlled by the timer.
After 15 seconds: After 15 seconds of running in the main loop, the HAL_TIM_PeriodElapsedCallback function starts, adjusting the timer and controlling the LED D3 blink pattern.

https://github.com/YrSk-tech/STM32_TIMbasis

## Input Capture App

Capture PWM frequency and duty cycle with Input Capture direct and indirect modes
https://github.com/YrSk-tech/STM32_IC

## PWM basis app

Changing brightness of LEDs (D2&D3) with pulse-width modulation

https://github.com/YrSk-tech/STM32_PWMbasis

## EXTI basis app

Controlling LEDs D2 and D3 with External Interrupt features by using button 

https://github.com/YrSk-tech/STM32_EXTIbasis/tree/main

## GPIO basis app

https://github.com/YrSk-tech/STM32_GPIObasis

Microcontroller STM32F4VE

Course name: Mastering STM32 microcontrollers
Link: https://www.udemy.com/course/mastering-stm32f407-microcontrollers/
