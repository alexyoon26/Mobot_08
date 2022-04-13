This starter code comes with several helper functions to help you write 
your project code.
myservo.write(angle); sets the servo angle, 90 degrees is nominally 
straight in front
Distance_test(); Reads the distance from the ultrasonic sensor, returns a 
float value
analogRead(LL); Reads the left light sensor, returns the value as an int
analogRead(LR); Reads the right light sensor, returns the value as an int
analogRead(LM); Reads the middle light sensor, returns the value as an int
Hint: All three light sensors may not behave the same way! Make sure to 
calibrate each individually.
leftMotor(speed, direction); Sets the speed and direction of the left 
motor.
Direction should be a boolean (you can input this as a 0 or 1).
Some motors are backwards, so make sure to test which direction is forward 
and backward. Returns void.
rightMotor(speed, direction); Sets the speed and direction of the right 
motor. Same hints as above apply.
Helpful functions:
Serial.print(value); Prints the value to the Serial monitor. Make sure 
your serial monitor is set to 9600 Baud Rate.
delay(value); Delays the code from running for value in milliseconds.
