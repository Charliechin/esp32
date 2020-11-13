# esp32
Blueprint

3.3-volt ====> VCC

GPIO 3 (U0R) ===> TX
GPIO 1 (U0T) ===> RX
GND => GND

* also set the FTDI to 3.3V plus jumping pin GPIO 0 to Ground in the ESP32-CAM. Remove it after programming.

So it goes like this:

To program:

FTDO to 3.3V
ESP32 CAM wire from GPIO0 to Ground

To test:

FTDO to 5V
Remove ESP32 Cam Wire from GPIO0
