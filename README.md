/*
blink321
========

Blink321 Arduino/C my addition to SparkFun lab Blink exercise 8/4/2012 at Open IT Lab at ITology in Columbia, SC

  Blink321 by Christine Tanner on 08/04/2012 at ITology lab sponsored by Open IT Lab and presented by SparkFun Electronics

Christine Tanner promotionsbychristine@gmail.com 

 Turns on LEDs on for a second in the shape of a 3 then off then in the shape of a 2 then off then in the shape of a 1 then off again and then repeats.
 
 I enhanced this code from the example code which was in the public domain for Blink.
 */

// An Arduino board was used and this was coded in C

// Blink321 (there is a video I took too)

int led0 = 2;
int led1 = 3;
int led2 = 4;
int led3 = 5;
int led4 = 6;
int led5 = 7;
int led6 = 8;
int led7 = 9;
int led8 = 10;
int led9 = 11;

// the setup routine runs once when you press reset:
void setup() {                
  // initialize the digital pin as an output.
  pinMode(led0, OUTPUT); 
  pinMode(led1, OUTPUT);
  pinMode (led2, OUTPUT); 
  pinMode (led3, OUTPUT); 
  pinMode (led4, OUTPUT); 
  pinMode (led5, OUTPUT); 
  pinMode (led6, OUTPUT); 
  pinMode (led7, OUTPUT); 
  pinMode (led8, OUTPUT); 
  pinMode (led9, OUTPUT); 
}

// the loop routine runs over and over again forever:
void loop() {
    
//The LEDs light up like the number 3

  digitalWrite(led0, HIGH); 
  digitalWrite(led1, HIGH);
 // digitalWrite(led2, HIGH);
  digitalWrite(led3, HIGH);
  digitalWrite(led4, HIGH);
  digitalWrite(led5, HIGH);
 // digitalWrite(led6, HIGH);
  digitalWrite(led7, HIGH);
  digitalWrite(led8, HIGH);
  digitalWrite(led9, HIGH);
  delay (1000);
  
// All LEDs go off
  digitalWrite(led0, LOW); 
  digitalWrite(led1, LOW);
  digitalWrite(led2, LOW);
  digitalWrite(led3, LOW);
  digitalWrite(led4, LOW);
  digitalWrite(led5, LOW);
  digitalWrite(led6, LOW);
  digitalWrite(led7, LOW);
  digitalWrite(led8, LOW);
  digitalWrite(led9, LOW);
  delay (1000);

//The LEDs light up like the number 2

  digitalWrite(led0, HIGH); 
  digitalWrite(led1, HIGH);
 // digitalWrite(led2, HIGH);
  digitalWrite(led3, HIGH);
  digitalWrite(led4, HIGH);
  digitalWrite(led5, HIGH);
  digitalWrite(led6, HIGH);
 // digitalWrite(led7, HIGH);
  digitalWrite(led8, HIGH);
  digitalWrite(led9, HIGH);
  delay (1000);
  
// All LEDs go off
  digitalWrite(led0, LOW); 
  digitalWrite(led1, LOW);
  digitalWrite(led2, LOW);
  digitalWrite(led3, LOW);
  digitalWrite(led4, LOW);
  digitalWrite(led5, LOW);
  digitalWrite(led6, LOW);
  digitalWrite(led7, LOW);
  digitalWrite(led8, LOW);
  digitalWrite(led9, LOW);
  delay (1000);


//The LEDs light up like the number 1

 // digitalWrite(led0, HIGH); 
  digitalWrite(led1, HIGH);
 // digitalWrite(led2, HIGH);
  digitalWrite(led3, HIGH);
 // digitalWrite(led4, HIGH);
  digitalWrite(led5, HIGH);
 // digitalWrite(led6, HIGH);
  digitalWrite(led7, HIGH);
//  digitalWrite(led8, HIGH);
  digitalWrite(led9, HIGH);
  delay (1000);

// All LEDs go off
  digitalWrite(led0, LOW); 
  digitalWrite(led1, LOW);
  digitalWrite(led2, LOW);
  digitalWrite(led3, LOW);
  digitalWrite(led4, LOW);
  digitalWrite(led5, LOW);
  digitalWrite(led6, LOW);
  digitalWrite(led7, LOW);
  digitalWrite(led8, LOW);
  digitalWrite(led9, LOW);
  delay (1000);
   
}


