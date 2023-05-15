# day 2
### led blinking without switch
![no loading](https://github.com/vivek445566123/internship/blob/main/Screenshot%20from%202023-05-09%2012-12-06.png)
### led blinking with switch
![no loading](https://github.com/vivek445566123/internship/blob/main/Screenshot%20from%202023-05-09%2012-32-41.png)
# day 3
### and gate
![no loading](https://github.com/vivek445566123/internship/blob/main/Screenshot%20from%202023-05-11%2010-44-20.png)
### ardunino blink
![no loading](https://github.com/vivek445566123/internship/blob/main/Screenshot%20from%202023-05-11%2011-12-11.png)
![no loading](https://github.com/vivek445566123/internship/blob/main/Screenshot%20from%202023-05-11%2014-18-35.png)
![no loading](https://github.com/vivek445566123/internship/blob/main/Screenshot%20from%202023-05-15%2014-07-34.png)
[tinker circuit](https://www.tinkercad.com/things/4WutSqH1nOg-smashing-jofo/editel)
# day 5
/*
  ReadAnalogVoltage
  Reads an analog input on pin 0, converts it to voltage, and prints the result to the serial monitor.

  OPEN THE SERIAL MONITOR TO VIEW THE OUTPUT >> 
  Attach the center pin of a potentiometer to pin A0, and the outside pins to +5V and ground.

  This example code is in the public domain.
*/


// the setup routine runs once when you press reset:
void setup() {
  // initialize serial communication at 9600 bits per second:
  Serial.begin(9600);
}

// the loop routine runs over and over again forever:
void loop() {
  // read the input on analog pin 0:
  int sensorValue = analogRead(A0);
  // Convert the analog reading (which goes from 0 - 1023) to a voltage (0 - 5V):
  float voltage = sensorValue * (5.0 / 1023.0);
  // print out the value you read:
  Serial.println(voltage);
}
