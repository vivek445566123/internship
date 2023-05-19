# Day-1
## 10 days internship
10 days internship
> 10 days internship in jyothi eng college


1. createbig size heading-add the symbol # before subject
2. for bold the letters [** subject **]
3. for continues numbering for the lines add the number with dot(1.) enter
4. write a program/code for copy -write the program in side backdot (```program```)
 
  
 ```
 #include <stdio.h>
int main() {
   // printf() displays the string inside quotation
   printf("Hello, World!");
   return 0;
}
```
[jomon123-123](https://www.github.com/jomon123-123) 
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
# day 4
>MACHINE LEARNING CLASS 
>
1.signal detector work
# day 5
### INTERFACING POTENTIOMETER USING ARDINO
![no loading](https://github.com/vivek445566123/internship/blob/main/Screenshot%20from%202023-05-15%2014-30-15.png)
6. **To select the code from the Tinkercad simulator**
- create the circuit with the components
- go to the cornor of the screen
- Then select button named as the ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%202023-05-11%20at%2013-39-33%20Circuit%20design%20Tremendous%20Jarv%20Tinkercad.png) 
- select the TEXT 
- After the selection it will show the related code ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%202023-05-11%20at%2011-33-09%20Circuit%20design%20Tremendous%20Jarv%20Tinkercad.png)
7. **program for 2 led blinking**
```
// C++ code
//
void setup()
{
  pinMode(8, OUTPUT);
  pinMode(13, OUTPUT);
}

void loop()
{
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
   digitalWrite(8, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1500 millisecond(s)
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1500 millisecond(s)
}
```
8. related image [Tinker the circuit](https://www.tinkercad.com/things/bFUZMSDS44M-arduino-led-blinking/editel)  ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-11%2012-46-39.png) 
9. **3 LED circuit with Arduino**  [Tinker the circuit](https://www.tinkercad.com/things/bbfA9LHBrRQ-copy-of-arduino-led-blinking/editel)  ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-11%2014-22-24.png)
**Program**
```
// C++ code
//
void setup()
{
  pinMode(8, OUTPUT);
  pinMode(13, OUTPUT);
  pinMode(2, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(800); // Wait for 800 millisecond(s)
   digitalWrite(13, LOW);
  delay(800); // Wait for 800 millisecond(s)
  digitalWrite(8, HIGH);
  delay(800); // Wait for 800 millisecond(s)
  digitalWrite(8, LOW);
  delay(800); // Wait for 800 millisecond(s)
  digitalWrite(2, HIGH);
  delay(800); // Wait for 800 millisecond(s)
   digitalWrite(2, LOW);
  delay(800); // Wait for 800 millisecond(s)
}
```
# Day-4
> introduction to AI & ML
1. Introduced a programming platform named as [Blockly](https://developers.google.com/blockly) ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-12%2010-34-11.png)
2. The platform like Blockly are mostly used by  fresher's in programming
3. It's like a game 
4. The blockly helps to know about the programming easly
5. To create a multifunction program like a calculator ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-12%2012-21-17.png)
**AI & ML** 
> STM 32 NUCLEO DEVELOPMENT BOARD
 
![IMAGE](https://github.com/kpr22102210/10-Days-internship/blob/main/img/stm32.jpg)
1. The board is programmeble
2. Can program th board by nucleo software
3. It can build a sound detecting device by using microphone sensor 

# Day-5
> Introducing drones by NAVANEETH 3rd year student of robotics
1. Introducing Drones
2. explained about drones parts
3. also speaked about the technical specifications like (Thrust,altitude,propeler diamention,weight management) 
4. To config the drones with software named as mission planner  ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%202023-05-16%20at%2009-28-33%20mission%20planner%20-%20Google%20Search.png)
> Analog reader potentiometer
5. [tinker the circuit](https://www.tinkercad.com/things/dFZMDWtXe0k-pot-with-arduino/editel)
![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-15%2014-28-50.png)
2. related program shown in below

**program**
```
const int potpin=A0;

void setup() {
   Serial.begin(9600);
}
void loop() {
  int potValue =analogRead(potpin);
  Serial.println(potValue);
  delay(100);
}
```
# Day-6
 > Basics of 3D printing conducted by 3rd year student robotics
1. first introduced of the 3d printing
2. creating  models by the tinkercad 3D modeling
3. start with basic shapes
4. also cover the previous design's
5. created a base and top cover for the flower bottel by using [Tinkercad](https://www.tinkercad.com/)
6. then introduced the 3D printer 
7. also printed a design (duration 19 min)
# Day-7
> Introduced the yaskawa arm robot
1. The introduction of yaskawa AR1440 
![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/hhh.jpeg)
> Then introduced about the EV (electric vehicle)
# Day-8
> Arduino 
1. Programming the arduino for the 7 segment display with pot 
2. adjusting the speed of the display by varing the pot [thinker the circuit](https://www.tinkercad.com/things/7hNg1XcCvKV-copy-of-fantastic-gaaris-jaiks/editel)  ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-18%2010-51-29.png)

**program**
```
// C++ code
//
const int potpin=A0;


void setup()
  
{
  Serial.begin(9600);
  pinMode(13, OUTPUT);
  pinMode(12,OUTPUT);
  pinMode(11,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(9,OUTPUT);
  pinMode(8,OUTPUT);
  pinMode(7,OUTPUT);
}

void loop()
{
  int potValue =analogRead(potpin);
  Serial.println(potValue);
  digitalWrite(13, LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,HIGH);
  delay(potValue); // Wait for 1000 millisecond(s
  digitalWrite(11,LOW);
  digitalWrite(12,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,LOW);
  digitalWrite(10,LOW);
  digitalWrite(8,HIGH);
  digitalWrite(11,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  delay(potValue);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(10,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(12,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(12,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  delay(potValue);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  delay(potValue);
  
  delay(potValue); // Wait for 1000 millisecond(s)
}
```


