## Modified Files

- `user_interface.cpp`  
  - Updated the display initialization to support 16×2 LCD instead of 20×4.
  - Changed the code that prints temperature, gas, and alarm status on two lines.

- `display.cpp`
  - Updated the DDRAM address definitions for a 16×2 LCD.
  - Removed support for lines 2 and 3.
