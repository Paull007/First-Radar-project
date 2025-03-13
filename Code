const int trig = 5;
const int echo = 6;
const int led1 = 7;    // LED 1 on digital pin 9
const int led2 = 8;   // LED 2 on digital pin 10

long totaltime;
int distance;

void setup() {
  pinMode(trig, OUTPUT);
  pinMode(echo, INPUT);
  pinMode(led1, OUTPUT);
  pinMode(led2, OUTPUT);
  Serial.begin(9600);
}

void loop() {
  // Send ultrasonic pulse
  digitalWrite(trig, LOW);
  delayMicroseconds(2);
  digitalWrite(trig, HIGH);
  delayMicroseconds(10);
  digitalWrite(trig, LOW);

  totaltime = pulseIn(echo, HIGH, 30000);
  if (totaltime == 0) {
    Serial.println("No echo received");
    return;
  }

  // Calculate distance (in centimeters)
  distance = totaltime * 0.034 / 2;
  Serial.print("Distance: ");
  Serial.println(distance);

  int blinkDelay = map(distance, 10, 50, 100, 500);
  blinkDelay = constrain(blinkDelay, 100, 500); 


  digitalWrite(led1, HIGH);
  delay(blinkDelay / 2);
  digitalWrite(led1, LOW);
  
  digitalWrite(led2, HIGH);
  delay(blinkDelay / 2);
  digitalWrite(led2, LOW);
}
