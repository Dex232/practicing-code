  int  RED1;
  int  RED2;
  int  YELLOW1;
  int  YELLOW2;
  int GREEN;

void setup() {
    RED1 = 2;
    RED2 = 3;
    YELLOW1 = 10;
    YELLOW2 = 11;
    GREEN = 7;
  pinMode (RED1, OUTPUT);
  pinMode (RED2, OUTPUT);
  pinMode (YELLOW1, OUTPUT);
  pinMode (YELLOW2, OUTPUT);
  pinMode (GREEN, OUTPUT);
  
}

void loop() {

}

//RED1
  void RED1();
  digitalWrite(RED1,HIGH);
  delay(500);
  digitalWrite(RED1,LOW);
  delay(500);
  }
//RED2
  void RED2(){
  digitalWrite(RED2,HIGH);
  delay(500);
  digitalWrite(RED2,LOW);
  delay(500);
  }
//  YELLOW1
  void YELLOW1(){
  digitalWrite(YELLOW1,HIGH);
  delay(500);
  digitalWrite(YELLOW1,LOW);
  delay(500);
  }
//  YELLOW2
  void YELLOW1(){
  digitalWrite(YELLOW2,HIGH);
  delay(500);
  digitalWrite(YELLOW2,LOW);
  delay(500);
  }
//  GREEN
  void GREEN(){
  digitalWrite(GREEN,HIGH);
  delay(500);
  digitalWrite(GREEN,LOW);
  delay(500);
  }
