# turn-on-led-using-a-switch-button

led-on-using-switch-button

AIM:-to make a led Bulb on and off using switch button.

EQUIPMENT USED:-led,breadboard,connecting wires,switch button,resistors.

CODE:-void setup()

{

pinMode(8,output);

pinmode(2,output);

}

void loop() {

int A=digitalWrite(8);

if(A == HIGH)


{

digitalWrite(2,HIGH);

}

else

{

digitalWrite(2,LOW);

}

}

LEARNING OUTCOMES:-1.learned how turn on led using a switch/push button.

PRECAUTION/ERROR:-1.Connection should be correct. 2.LEDs should be working.

