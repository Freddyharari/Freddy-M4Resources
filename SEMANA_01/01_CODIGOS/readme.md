int counter;

void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(200); 
  digitalWrite(LED_BUILTIN, LOW);
  delay(200); 
  digitalWrite(LED_BUILTIN, HIGH);
  delay(200); 
  digitalWrite(LED_BUILTIN, LOW);
  for (counter = 0; counter < 10; ++counter) {
    digitalWrite(LED_BUILTIN, HIGH);
  }
}
