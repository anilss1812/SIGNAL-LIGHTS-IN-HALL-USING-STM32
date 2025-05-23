In this assignment, I developed a simple vehicle indicator system using the STM32F103C6 microcontroller (commonly used in Blue Pill boards). The project includes two push buttons: one for the right indicator and one for the left. When the right button is pressed, the right LED blinks; when the left button is pressed, the left LED blinks.

The program was written in Embedded C using STM32CubeIDE, and the GPIO pins were configured using STM32CubeMX. I used HAL libraries for reading the button states and toggling the LEDs. A basic delay was added for blinking and button debounce.

This project helped me understand the basics of GPIO configuration, button input handling, and LED output control on the STM32F103C6. I also learned how to simulate this system in Proteus using a virtual STM32F103C6 and external components.

