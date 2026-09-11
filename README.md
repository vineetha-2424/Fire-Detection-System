# Fire-Detection-System
int flame = 7;
int buzzer = 8;

void setup() {
  pinMode(flame, INPUT);
  pinMode(buzzer, OUTPUT);
}

void loop() {
  if (digitalRead(flame) == LOW)
    digitalWrite(buzzer, HIGH);
  else
    digitalWrite(buzzer, LOW);
}
