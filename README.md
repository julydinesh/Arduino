# Arduino

* Arduino based projects and source code. Sample LED Blink.
* Flash the below code in ARDUINO UNO R3 and then power it up to see the O/P

int ledPin = 13; // define the digital pin for LED output

void setup() 
{
  pinMode(ledPin, OUTPUT); // set the LED pin as output
}

void loop() 
{
  digitalWrite(ledPin, HIGH); // turn the LED on
  delay(1000); // wait for 1 second
  digitalWrite(ledPin, LOW); // turn the LED off
  delay(1000); // wait for 1 second
}
