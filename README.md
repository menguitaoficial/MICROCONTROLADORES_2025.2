# MICROCONTROLADORES_2025.2
Colocar o projeto do tinkcard
Aula 1 - 12/08/2025
byte led = 7; 
  
void setup()
{
  pinMode(led, OUTPUT);
}

void loop()
{
  digitalWrite(led, HIGH);
  delay(1000);
  digitalWrite(led, LOW);
  delay(1000);
}
