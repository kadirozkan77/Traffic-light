int redLight = 10;
int yellowLight = 9;
int greenLight = 8;

void setup() {

  pinMode(redLight, OUTPUT);
  pinMode(yellowLight, OUTPUT);
  pinMode(greenLight, OUTPUT);
}

void loop() {
  digitalWrite(redLight, HIGH);  
  digitalWrite(yellowLight, LOW); 
  digitalWrite(greenLight, LOW);  
  delay(5000);                    

  
  digitalWrite(redLight, LOW);    
  digitalWrite(yellowLight, LOW); 
  digitalWrite(greenLight, HIGH); 
  delay(5000);                    

  
  digitalWrite(redLight, LOW);    
  digitalWrite(yellowLight, HIGH);
  digitalWrite(greenLight, LOW);  
  delay(2000);                   
}
