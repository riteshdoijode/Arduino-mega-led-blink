# Arduino Mega - Blink LED

This project demonstrates the basic **Blink** example on an Arduino Mega board.  
It blinks the built-in LED (connected to pin **13**) on and off at 1-second intervals.

## Hardware Required
- Arduino Mega 2560
- USB cable

*(No extra components are required, since the built-in LED is used. If you want to use an external LED, connect it to any digital pin with a 220Ω–330Ω resistor.)*

``` void setup() ```
Runs once when the Arduino is powered on or reset.

pinMode(13, OUTPUT); → Configures digital pin 13 as an output pin so it can control the LED.

``` void loop() ```
Runs continuously after setup().

``` digitalWrite(13, HIGH); ``` → Turns the LED on.

``` delay(1000); ``` → Pauses the program for 1000 milliseconds (1 second).

``` digitalWrite(13, LOW); ``` → Turns the LED off.

``` delay(1000); ``` → Pauses again for 1 second before repeating.

## How to Run
1. Install the [Arduino IDE](https://www.arduino.cc/en/software).  
2. Open the code in the IDE.  
3. Select **Arduino Mega 2560** as your board.  
4. Connect your Arduino Mega via USB.  
5. Click **Upload**.  
6. The onboard LED will start blinking! 
