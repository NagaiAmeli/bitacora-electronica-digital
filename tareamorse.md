Drive con el video
https://drive.google.com/file/d/17biSaH7FlvwXgt_kthkt-W7RfwQwHQrP/view?usp=sharing





int patitaLed = 9;
void setup() {
  //la patita 9 se va a comportar como SALIDA
  pinMode(patitaLed, OUTPUT);
}
void loop() {
 
  //2 argumentos: la patita, y si es HIGH o LOW

  // el .
  //punto();
  // la -
  //raya();

 punto(); raya(); //a

 delay(2000);

 punto(); raya(); punto(); //r
 delay(500);
 punto(); punto(); //i
 delay(500);
 punto(); punto(); punto(); raya(); //v
 delay(500);
 punto(); //e
 delay(500);
 punto(); raya(); punto(); //r
  
 delay(2000); 

 punto(); raya(); raya(); // w
 delay(500);
 punto(); punto(); //i
 delay(500);
 punto(); raya(); punto(); punto(); //l
 delay(500);
 punto(); raya(); punto(); punto(); //l
 
 delay(2000);

 punto(); punto(); raya(); punto(); //f
  delay(500);
 punto(); raya(); punto(); punto(); //l
  delay(500);
 raya(); raya(); raya(); //o
  delay(500);
punto(); raya(); raya(); // w






  delay(3000); //para cerrar antes de un loop
}

void punto(){
  // esta función va a escribir un punto en mi led
  // el .
  digitalWrite(patitaLed, HIGH);
  delay(1000); //delay se coloca en milisegundos
  digitalWrite(patitaLed, LOW);
  delay(1000);
}

void raya(){
  digitalWrite(patitaLed, HIGH);
  delay(2000); //delay se coloca en milisegundos
  digitalWrite(patitaLed, LOW);
  delay(1000);
  //menos de dos minutos en total
}
