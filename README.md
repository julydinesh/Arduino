# Arduino

* Arduino based projects and source code. Sample LED Blink.
* Flash the below code in ARDUINO UNO R3 and then power it up to see the O/P with a delay of 1 second

int ledPin = 13; // define the digital pin for LED output

void setup() 
{
  pinMode(ledPin, OUTPUT); 
}

void loop() 
{
  digitalWrite(ledPin, HIGH); 
  delay(1000); 
  digitalWrite(ledPin, LOW); 
  delay(1000); 
}
