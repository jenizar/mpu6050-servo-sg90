# mpu6050-servo-sg90
Control servo using MPU6050 Gyroscope with Arduino

materials:

arduino nano, gyro sensor mpu6050, motor servo sg90, battery 9v, cable jumper

wiring:

MPU6050 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Arduino Nano

Vcc &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; --  &nbsp;&nbsp;&nbsp;&nbsp;+5V

Gnd &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; --  &nbsp;&nbsp;&nbsp;&nbsp;Gnd

SDA &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; --  &nbsp;&nbsp;&nbsp;&nbsp;A4

SCL &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; --  &nbsp;&nbsp;&nbsp;&nbsp;A5

INT &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; --  &nbsp;&nbsp;&nbsp;&nbsp;D2

Servo SG90 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Arduino Nano

Vcc &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; --  &nbsp;&nbsp;&nbsp;&nbsp;+5V

Gnd &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; --  &nbsp;&nbsp;&nbsp;&nbsp;Gnd

Data &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; --  &nbsp;&nbsp;&nbsp;&nbsp;D9


#define INTERRUPT_PIN 2  // use pin 2 on Arduino Uno & most boards

#define SERVO_PIN 9 // use pin 9 for servo control

reference:

https://youtu.be/vSKEH0FwhUE
