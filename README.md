# Arduino Mega - Blink LED

This project demonstrates the basic **Blink** example on an Arduino Mega board.  
It blinks the built-in LED (connected to pin **13**) on and off at 1-second intervals.

## Hardware Required
- Arduino Mega 2560
- USB cable

*(No extra components are required, since the built-in LED is used. If you want to use an external LED, connect it to any digital pin with a 220Ω–330Ω resistor.)*

## Code

```cpp
// Blink the built-in LED on Arduino Mega

void setup() {
  // initialize digital pin 13 (built-in LED) as an output.
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);   // turn the LED on
  delay(1000);              // wait for a second
  digitalWrite(13, LOW);    // turn the LED off
  delay(1000);              // wait for a second
}
