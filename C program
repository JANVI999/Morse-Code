Morse code encoder

const int ledPin = 8;
const int SpeakerPin = 12;
String code = "";
int len = 0;
char ch;
char new_char;
int unit_delay = 500;

void turnONLed()
{
  //Turn ON LED
  digitalWrite(ledPin, HIGH);
  //delay(1000);
}

void turnONSpeaker()
{
  tone(SpeakerPin, 4699, 300); // tone(speakerPin, frequency, duration in milliSec)
}

void dot()
{
Serial.print(".");
turnONLed();
delay(unit_delay);
digitalWrite(ledPin, LOW);

}
void dash()
{
Serial.print("-");
turnONSpeaker();
delay(unit_delay * 3);

}
void A()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void B()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void C()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void D()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void E()
{
dot();
delay(unit_delay);
}
void f()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void G()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void H()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void I()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void J()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void K()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void L()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void M()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void N()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void O()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void P()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
}
void Q()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void R()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void S()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void T()
{
dash();
delay(unit_delay);
}
void U()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void V()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void W()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void X()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void Y()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void Z()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void one()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void two()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void three()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void four()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void five()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void six()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void seven()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void eight()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void nine()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void zero()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void morse()
{
if (ch == 'A' || ch == 'a')
{
A();
Serial.print(" ");
}
else if (ch == 'B' || ch == 'b')
{
B();
Serial.print(" ");
}
else if (ch == 'C' || ch == 'c')
{
C();
Serial.print(" ");
}
else if (ch == 'D' || ch == 'd')
{
D();
Serial.print(" ");
}
else if (ch == 'E' || ch == 'e')
{
E();
Serial.print(" ");
}
else if (ch == 'f' || ch == 'f')
{
f();
Serial.print(" ");
}
else if (ch == 'G' || ch == 'g')
{
G();
Serial.print(" ");
}
else if (ch == 'H' || ch == 'h')
{
H();
Serial.print(" ");
}
else if (ch == 'I' || ch == 'i')
{
I();
Serial.print(" ");
}
else if (ch == 'J' || ch == 'j')
{
J();
Serial.print(" ");
}
else if (ch == 'K' || ch == 'k')
{
K();
Serial.print(" ");
}
else if (ch == 'L' || ch == 'l')
{
L();
Serial.print(" ");
}
else if (ch == 'M' || ch == 'm')
{
M();
Serial.print(" ");
}
else if (ch == 'N' || ch == 'n')
{
N();
Serial.print(" ");
}
else if (ch == 'O' || ch == 'o')
{
O();
Serial.print(" ");
}
else if (ch == 'P' || ch == 'p')
{
P();
Serial.print(" ");
}
else if (ch == 'Q' || ch == 'q')
{
Q();
Serial.print(" ");
}
else if (ch == 'R' || ch == 'r')
{
R();
Serial.print(" ");
}
else if (ch == 'S' || ch == 's')
{
S();
Serial.print(" ");
}
else if (ch == 'T' || ch == 't')
{
T();
Serial.print(" ");
}
else if (ch == 'U' || ch == 'u')
{
U();
Serial.print(" ");
}
else if (ch == 'V' || ch == 'v')
{
V();
Serial.print(" ");
}
else if (ch == 'W' || ch == 'w')
{
W();
Serial.print(" ");
}
else if (ch == 'X' || ch == 'x')
{
X();
Serial.print(" ");
}
else if (ch == 'Y' || ch == 'y')
{
Y();
Serial.print(" ");
}
else if (ch == 'Z' || ch == 'z')
{
Z();
Serial.print(" ");
}
else if (ch == '0')
{
zero();
Serial.print(" ");
}
else if (ch == '1')
{
one();
Serial.print(" ");
}
else if (ch == '2')
{
two();
Serial.print(" ");
}
else if (ch == '3')
{
three();
Serial.print(" ");
}
else if (ch == '4')
{
four();
Serial.print(" ");
}
else if (ch == '5')
{
five();
Serial.print(" ");
}
else if (ch == '6')
{
six();
Serial.print(" ");
}
else if (ch == '7')
{
seven();
Serial.print(" ");
}
else if (ch == '8')
{
eight();
Serial.print(" ");
}
else if (ch == '9')
{
nine();
Serial.print(" ");
}
else if(ch == ' ')
{
delay(unit_delay*7);
Serial.print("/ ");
}
else
Serial.println(" ");
}
void String2Morse()
{
len = code.length();
for (int i = 0; i < len; i++)
{
ch = code.charAt(i);
morse();
}
}
void setup() {
Serial.begin(9600);
pinMode(ledPin, OUTPUT);
pinMode(SpeakerPin, OUTPUT);
Serial.println("----------Morse code encoder----------");
Serial.println("Enter text: ");
}
void loop() {
while (Serial.available())
{
code = Serial.readString();
Serial.print(code);
Serial.print("Encoded text in morse code: ");
Serial.print(" = ");
String2Morse();
Serial.println("");
}
delay(1000);
}const int ledPin = 8;
const int SpeakerPin = 12;
String code = "";
int len = 0;
char ch;
char new_char;
int unit_delay = 500;

void turnONLed()
{
  //Turn ON LED
  digitalWrite(ledPin, HIGH);
  //delay(1000);
}

void turnONSpeaker()
{
  tone(SpeakerPin, 4699, 300); // tone(speakerPin, frequency, duration in milliSec)
}

void dot()
{
Serial.print(".");
turnONLed();
delay(unit_delay);
digitalWrite(ledPin, LOW);

}
void dash()
{
Serial.print("-");
turnONSpeaker();
delay(unit_delay * 3);

}
void A()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void B()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void C()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void D()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void E()
{
dot();
delay(unit_delay);
}
void f()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void G()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void H()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void I()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void J()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void K()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void L()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void M()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void N()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void O()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void P()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
}
void Q()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void R()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void S()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void T()
{
dash();
delay(unit_delay);
}
void U()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void V()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void W()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void X()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void Y()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void Z()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void one()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void two()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void three()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void four()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void five()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void six()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void seven()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void eight()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void nine()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void zero()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void morse()
{
if (ch == 'A' || ch == 'a')
{
A();
Serial.print(" ");
}
else if (ch == 'B' || ch == 'b')
{
B();
Serial.print(" ");
}
else if (ch == 'C' || ch == 'c')
{
C();
Serial.print(" ");
}
else if (ch == 'D' || ch == 'd')
{
D();
Serial.print(" ");
}
else if (ch == 'E' || ch == 'e')
{
E();
Serial.print(" ");
}
else if (ch == 'f' || ch == 'f')
{
f();
Serial.print(" ");
}
else if (ch == 'G' || ch == 'g')
{
G();
Serial.print(" ");
}
else if (ch == 'H' || ch == 'h')
{
H();
Serial.print(" ");
}
else if (ch == 'I' || ch == 'i')
{
I();
Serial.print(" ");
}
else if (ch == 'J' || ch == 'j')
{
J();
Serial.print(" ");
}
else if (ch == 'K' || ch == 'k')
{
K();
Serial.print(" ");
}
else if (ch == 'L' || ch == 'l')
{
L();
Serial.print(" ");
}
else if (ch == 'M' || ch == 'm')
{
M();
Serial.print(" ");
}
else if (ch == 'N' || ch == 'n')
{
N();
Serial.print(" ");
}
else if (ch == 'O' || ch == 'o')
{
O();
Serial.print(" ");
}
else if (ch == 'P' || ch == 'p')
{
P();
Serial.print(" ");
}
else if (ch == 'Q' || ch == 'q')
{
Q();
Serial.print(" ");
}
else if (ch == 'R' || ch == 'r')
{
R();
Serial.print(" ");
}
else if (ch == 'S' || ch == 's')
{
S();
Serial.print(" ");
}
else if (ch == 'T' || ch == 't')
{
T();
Serial.print(" ");
}
else if (ch == 'U' || ch == 'u')
{
U();
Serial.print(" ");
}
else if (ch == 'V' || ch == 'v')
{
V();
Serial.print(" ");
}
else if (ch == 'W' || ch == 'w')
{
W();
Serial.print(" ");
}
else if (ch == 'X' || ch == 'x')
{
X();
Serial.print(" ");
}
else if (ch == 'Y' || ch == 'y')
{
Y();
Serial.print(" ");
}
else if (ch == 'Z' || ch == 'z')
{
Z();
Serial.print(" ");
}
else if (ch == '0')
{
zero();
Serial.print(" ");
}
else if (ch == '1')
{
one();
Serial.print(" ");
}
else if (ch == '2')
{
two();
Serial.print(" ");
}
else if (ch == '3')
{
three();
Serial.print(" ");
}
else if (ch == '4')
{
four();
Serial.print(" ");
}
else if (ch == '5')
{
five();
Serial.print(" ");
}
else if (ch == '6')
{
six();
Serial.print(" ");
}
else if (ch == '7')
{
seven();
Serial.print(" ");
}
else if (ch == '8')
{
eight();
Serial.print(" ");
}
else if (ch == '9')
{
nine();
Serial.print(" ");
}
else if(ch == ' ')
{
delay(unit_delay*7);
Serial.print("/ ");
}
else
Serial.println(" ");
}
void String2Morse()
{
len = code.length();
for (int i = 0; i < len; i++)
{
ch = code.charAt(i);
morse();
}
}
void setup() {
Serial.begin(9600);
pinMode(ledPin, OUTPUT);
pinMode(SpeakerPin, OUTPUT);
Serial.println("----------Morse code encoder----------");
Serial.println("Enter text: ");
}
void loop() {
while (Serial.available())
{
code = Serial.readString();
Serial.print(code);
Serial.print("Encoded text in morse code: ");
Serial.print(" = ");
String2Morse();
Serial.println("");
}
delay(1000);
}const int ledPin = 8;
const int SpeakerPin = 12;
String code = "";
int len = 0;
char ch;
char new_char;
int unit_delay = 500;

void turnONLed()
{
  //Turn ON LED
  digitalWrite(ledPin, HIGH);
  //delay(1000);
}

void turnONSpeaker()
{
  tone(SpeakerPin, 4699, 300); // tone(speakerPin, frequency, duration in milliSec)
}

void dot()
{
Serial.print(".");
turnONLed();
delay(unit_delay);
digitalWrite(ledPin, LOW);

}
void dash()
{
Serial.print("-");
turnONSpeaker();
delay(unit_delay * 3);

}
void A()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void B()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void C()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void D()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void E()
{
dot();
delay(unit_delay);
}
void f()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void G()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void H()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void I()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void J()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void K()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void L()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void M()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void N()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void O()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void P()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
}
void Q()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void R()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void S()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void T()
{
dash();
delay(unit_delay);
}
void U()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void V()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void W()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void X()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void Y()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void Z()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void one()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void two()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void three()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void four()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void five()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void six()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void seven()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void eight()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void nine()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void zero()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void morse()
{
if (ch == 'A' || ch == 'a')
{
A();
Serial.print(" ");
}
else if (ch == 'B' || ch == 'b')
{
B();
Serial.print(" ");
}
else if (ch == 'C' || ch == 'c')
{
C();
Serial.print(" ");
}
else if (ch == 'D' || ch == 'd')
{
D();
Serial.print(" ");
}
else if (ch == 'E' || ch == 'e')
{
E();
Serial.print(" ");
}
else if (ch == 'f' || ch == 'f')
{
f();
Serial.print(" ");
}
else if (ch == 'G' || ch == 'g')
{
G();
Serial.print(" ");
}
else if (ch == 'H' || ch == 'h')
{
H();
Serial.print(" ");
}
else if (ch == 'I' || ch == 'i')
{
I();
Serial.print(" ");
}
else if (ch == 'J' || ch == 'j')
{
J();
Serial.print(" ");
}
else if (ch == 'K' || ch == 'k')
{
K();
Serial.print(" ");
}
else if (ch == 'L' || ch == 'l')
{
L();
Serial.print(" ");
}
else if (ch == 'M' || ch == 'm')
{
M();
Serial.print(" ");
}
else if (ch == 'N' || ch == 'n')
{
N();
Serial.print(" ");
}
else if (ch == 'O' || ch == 'o')
{
O();
Serial.print(" ");
}
else if (ch == 'P' || ch == 'p')
{
P();
Serial.print(" ");
}
else if (ch == 'Q' || ch == 'q')
{
Q();
Serial.print(" ");
}
else if (ch == 'R' || ch == 'r')
{
R();
Serial.print(" ");
}
else if (ch == 'S' || ch == 's')
{
S();
Serial.print(" ");
}
else if (ch == 'T' || ch == 't')
{
T();
Serial.print(" ");
}
else if (ch == 'U' || ch == 'u')
{
U();
Serial.print(" ");
}
else if (ch == 'V' || ch == 'v')
{
V();
Serial.print(" ");
}
else if (ch == 'W' || ch == 'w')
{
W();
Serial.print(" ");
}
else if (ch == 'X' || ch == 'x')
{
X();
Serial.print(" ");
}
else if (ch == 'Y' || ch == 'y')
{
Y();
Serial.print(" ");
}
else if (ch == 'Z' || ch == 'z')
{
Z();
Serial.print(" ");
}
else if (ch == '0')
{
zero();
Serial.print(" ");
}
else if (ch == '1')
{
one();
Serial.print(" ");
}
else if (ch == '2')
{
two();
Serial.print(" ");
}
else if (ch == '3')
{
three();
Serial.print(" ");
}
else if (ch == '4')
{
four();
Serial.print(" ");
}
else if (ch == '5')
{
five();
Serial.print(" ");
}
else if (ch == '6')
{
six();
Serial.print(" ");
}
else if (ch == '7')
{
seven();
Serial.print(" ");
}
else if (ch == '8')
{
eight();
Serial.print(" ");
}
else if (ch == '9')
{
nine();
Serial.print(" ");
}
else if(ch == ' ')
{
delay(unit_delay*7);
Serial.print("/ ");
}
else
Serial.println(" ");
}
void String2Morse()
{
len = code.length();
for (int i = 0; i < len; i++)
{
ch = code.charAt(i);
morse();
}
}
void setup() {
Serial.begin(9600);
pinMode(ledPin, OUTPUT);
pinMode(SpeakerPin, OUTPUT);
Serial.println("----------Morse code encoder----------");
Serial.println("Enter text: ");
}
void loop() {
while (Serial.available())
{
code = Serial.readString();
Serial.print(code);
Serial.print("Encoded text in morse code: ");
Serial.print(" = ");
String2Morse();
Serial.println("");
}
delay(1000);
}const int ledPin = 8;
const int SpeakerPin = 12;
String code = "";
int len = 0;
char ch;
char new_char;
int unit_delay = 500;

void turnONLed()
{
  //Turn ON LED
  digitalWrite(ledPin, HIGH);
  //delay(1000);
}

void turnONSpeaker()
{
  tone(SpeakerPin, 4699, 300); // tone(speakerPin, frequency, duration in milliSec)
}

void dot()
{
Serial.print(".");
turnONLed();
delay(unit_delay);
digitalWrite(ledPin, LOW);

}
void dash()
{
Serial.print("-");
turnONSpeaker();
delay(unit_delay * 3);

}
void A()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void B()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void C()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void D()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void E()
{
dot();
delay(unit_delay);
}
void f()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void G()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void H()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void I()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void J()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void K()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void L()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void M()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void N()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void O()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void P()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
}
void Q()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void R()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void S()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void T()
{
dash();
delay(unit_delay);
}
void U()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void V()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void W()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void X()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void Y()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void Z()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void one()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void two()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void three()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void four()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void five()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void six()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void seven()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void eight()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void nine()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void zero()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void morse()
{
if (ch == 'A' || ch == 'a')
{
A();
Serial.print(" ");
}
else if (ch == 'B' || ch == 'b')
{
B();
Serial.print(" ");
}
else if (ch == 'C' || ch == 'c')
{
C();
Serial.print(" ");
}
else if (ch == 'D' || ch == 'd')
{
D();
Serial.print(" ");
}
else if (ch == 'E' || ch == 'e')
{
E();
Serial.print(" ");
}
else if (ch == 'f' || ch == 'f')
{
f();
Serial.print(" ");
}
else if (ch == 'G' || ch == 'g')
{
G();
Serial.print(" ");
}
else if (ch == 'H' || ch == 'h')
{
H();
Serial.print(" ");
}
else if (ch == 'I' || ch == 'i')
{
I();
Serial.print(" ");
}
else if (ch == 'J' || ch == 'j')
{
J();
Serial.print(" ");
}
else if (ch == 'K' || ch == 'k')
{
K();
Serial.print(" ");
}
else if (ch == 'L' || ch == 'l')
{
L();
Serial.print(" ");
}
else if (ch == 'M' || ch == 'm')
{
M();
Serial.print(" ");
}
else if (ch == 'N' || ch == 'n')
{
N();
Serial.print(" ");
}
else if (ch == 'O' || ch == 'o')
{
O();
Serial.print(" ");
}
else if (ch == 'P' || ch == 'p')
{
P();
Serial.print(" ");
}
else if (ch == 'Q' || ch == 'q')
{
Q();
Serial.print(" ");
}
else if (ch == 'R' || ch == 'r')
{
R();
Serial.print(" ");
}
else if (ch == 'S' || ch == 's')
{
S();
Serial.print(" ");
}
else if (ch == 'T' || ch == 't')
{
T();
Serial.print(" ");
}
else if (ch == 'U' || ch == 'u')
{
U();
Serial.print(" ");
}
else if (ch == 'V' || ch == 'v')
{
V();
Serial.print(" ");
}
else if (ch == 'W' || ch == 'w')
{
W();
Serial.print(" ");
}
else if (ch == 'X' || ch == 'x')
{
X();
Serial.print(" ");
}
else if (ch == 'Y' || ch == 'y')
{
Y();
Serial.print(" ");
}
else if (ch == 'Z' || ch == 'z')
{
Z();
Serial.print(" ");
}
else if (ch == '0')
{
zero();
Serial.print(" ");
}
else if (ch == '1')
{
one();
Serial.print(" ");
}
else if (ch == '2')
{
two();
Serial.print(" ");
}
else if (ch == '3')
{
three();
Serial.print(" ");
}
else if (ch == '4')
{
four();
Serial.print(" ");
}
else if (ch == '5')
{
five();
Serial.print(" ");
}
else if (ch == '6')
{
six();
Serial.print(" ");
}
else if (ch == '7')
{
seven();
Serial.print(" ");
}
else if (ch == '8')
{
eight();
Serial.print(" ");
}
else if (ch == '9')
{
nine();
Serial.print(" ");
}
else if(ch == ' ')
{
delay(unit_delay*7);
Serial.print("/ ");
}
else
Serial.println(" ");
}
void String2Morse()
{
len = code.length();
for (int i = 0; i < len; i++)
{
ch = code.charAt(i);
morse();
}
}
void setup() {
Serial.begin(9600);
pinMode(ledPin, OUTPUT);
pinMode(SpeakerPin, OUTPUT);
Serial.println("----------Morse code encoder----------");
Serial.println("Enter text: ");
}
void loop() {
while (Serial.available())
{
code = Serial.readString();
Serial.print(code);
Serial.print("Encoded text in morse code: ");
Serial.print(" = ");
String2Morse();
Serial.println("");
}
delay(1000);
}const int ledPin = 8;
const int SpeakerPin = 12;
String code = "";
int len = 0;
char ch;
char new_char;
int unit_delay = 500;

void turnONLed()
{
  //Turn ON LED
  digitalWrite(ledPin, HIGH);
  //delay(1000);
}

void turnONSpeaker()
{
  tone(SpeakerPin, 4699, 300); // tone(speakerPin, frequency, duration in milliSec)
}

void dot()
{
Serial.print(".");
turnONLed();
delay(unit_delay);
digitalWrite(ledPin, LOW);

}
void dash()
{
Serial.print("-");
turnONSpeaker();
delay(unit_delay * 3);

}
void A()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void B()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void C()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void D()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void E()
{
dot();
delay(unit_delay);
}
void f()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void G()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void H()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void I()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void J()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void K()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void L()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void M()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void N()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void O()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void P()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
}
void Q()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void R()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void S()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void T()
{
dash();
delay(unit_delay);
}
void U()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void V()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void W()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void X()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void Y()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void Z()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void one()
{
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void two()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void three()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void four()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dash();
delay(unit_delay);
}
void five()
{
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void six()
{
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void seven()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void eight()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
dot();
delay(unit_delay);
}
void nine()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dot();
delay(unit_delay);
}
void zero()
{
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
dash();
delay(unit_delay);
}
void morse()
{
if (ch == 'A' || ch == 'a')
{
A();
Serial.print(" ");
}
else if (ch == 'B' || ch == 'b')
{
B();
Serial.print(" ");
}
else if (ch == 'C' || ch == 'c')
{
C();
Serial.print(" ");
}
else if (ch == 'D' || ch == 'd')
{
D();
Serial.print(" ");
}
else if (ch == 'E' || ch == 'e')
{
E();
Serial.print(" ");
}
else if (ch == 'f' || ch == 'f')
{
f();
Serial.print(" ");
}
else if (ch == 'G' || ch == 'g')
{
G();
Serial.print(" ");
}
else if (ch == 'H' || ch == 'h')
{
H();
Serial.print(" ");
}
else if (ch == 'I' || ch == 'i')
{
I();
Serial.print(" ");
}
else if (ch == 'J' || ch == 'j')
{
J();
Serial.print(" ");
}
else if (ch == 'K' || ch == 'k')
{
K();
Serial.print(" ");
}
else if (ch == 'L' || ch == 'l')
{
L();
Serial.print(" ");
}
else if (ch == 'M' || ch == 'm')
{
M();
Serial.print(" ");
}
else if (ch == 'N' || ch == 'n')
{
N();
Serial.print(" ");
}
else if (ch == 'O' || ch == 'o')
{
O();
Serial.print(" ");
}
else if (ch == 'P' || ch == 'p')
{
P();
Serial.print(" ");
}
else if (ch == 'Q' || ch == 'q')
{
Q();
Serial.print(" ");
}
else if (ch == 'R' || ch == 'r')
{
R();
Serial.print(" ");
}
else if (ch == 'S' || ch == 's')
{
S();
Serial.print(" ");
}
else if (ch == 'T' || ch == 't')
{
T();
Serial.print(" ");
}
else if (ch == 'U' || ch == 'u')
{
U();
Serial.print(" ");
}
else if (ch == 'V' || ch == 'v')
{
V();
Serial.print(" ");
}
else if (ch == 'W' || ch == 'w')
{
W();
Serial.print(" ");
}
else if (ch == 'X' || ch == 'x')
{
X();
Serial.print(" ");
}
else if (ch == 'Y' || ch == 'y')
{
Y();
Serial.print(" ");
}
else if (ch == 'Z' || ch == 'z')
{
Z();
Serial.print(" ");
}
else if (ch == '0')
{
zero();
Serial.print(" ");
}
else if (ch == '1')
{
one();
Serial.print(" ");
}
else if (ch == '2')
{
two();
Serial.print(" ");
}
else if (ch == '3')
{
three();
Serial.print(" ");
}
else if (ch == '4')
{
four();
Serial.print(" ");
}
else if (ch == '5')
{
five();
Serial.print(" ");
}
else if (ch == '6')
{
six();
Serial.print(" ");
}
else if (ch == '7')
{
seven();
Serial.print(" ");
}
else if (ch == '8')
{
eight();
Serial.print(" ");
}
else if (ch == '9')
{
nine();
Serial.print(" ");
}
else if(ch == ' ')
{
delay(unit_delay*7);
Serial.print("/ ");
}
else
Serial.println(" ");
}
void String2Morse()
{
len = code.length();
for (int i = 0; i < len; i++)
{
ch = code.charAt(i);
morse();
}
}
void setup() {
Serial.begin(9600);
pinMode(ledPin, OUTPUT);
pinMode(SpeakerPin, OUTPUT);
Serial.println("----------Morse code encoder----------");
Serial.println("Enter text: ");
}
void loop() {
while (Serial.available())
{
code = Serial.readString();
Serial.print(code);
Serial.print("Encoded text in morse code: ");
Serial.print(" = ");
String2Morse();
Serial.println("");
}
delay(1000);
}












#define SIZE 26
const int ledPin=8;
const int speakerPin=12;
const int dotButton=2;
const int dashButton=7;

String morseCode="";
String text="";
int characterAscii=0;
int startPos=0, endPos=0;
int startPos1=0, endPos1=0;
String characterCode="";
int dashButtonState=0;
int dotButtonState=0;


//Array of MorseCode for letters of English Language A to Z
String letters[SIZE]={

// A to I
".-", "-...", "-.-.", "-..", ".", "..-.", "--.", "....", "..",
// J to R
".---", "-.-", ".-..", "--", "-.", "---", ".--.", "--.-", ".-.",
// S to Z
"...", "-", "..-", "...-", ".--", "-..-", "-.--", "--.."
};

       
void setup() {
  // put your setup code here, to run once:
//Getting things Ready
pinMode(ledPin, OUTPUT);
pinMode(dotButton, INPUT);
pinMode(dashButton, INPUT);
Serial.begin(9600);

Serial.println("*************************************************************");
Serial.println("                    Demonstration of Morse Code              ");
Serial.println("************************************************************* ");
Serial.println("\nInstructions");
Serial.println("1. First Write Your Morse code");
Serial.println("2. When you are done  Write 1 on above input box and Press Enter or click Send Button ");
Serial.println("3. For Space between letters write 2 and Press Enter ");
Serial.println("4. For Space between words   write 3 and Press Enter ");

Serial.println("5. Thats all Translation of Morse Code  will then be Shown ");

Serial.println("\n\nEnter Your Morse Code Here  ");

}


void loop() {
  // put your main code here, to run repeatedly:

while(Serial.available() > 0 )
{
      int ascii=Serial.read();

      switch(ascii)
      {
        case 49: // 49 is Ascii value of 1

        Serial.print("\n");
        morseCode.concat('#');// Placeing # at the end of morseCode to simplify further processing

         Serial.print("\nYour Morse code Translation :  ");
         
        endPos1=morseCode.indexOf('#');

        while(endPos1 < morseCode.length() )
        {
            extractLetters(morseCode.substring(startPos1, endPos1)); // This function would extract Letter as name suggest and would convert  code to text SIMPLE!
           startPos1=endPos1+1;
           if(startPos1 == morseCode.length() )
           {
              break;
           }
           endPos1= morseCode.indexOf('#', startPos1);
        }
        startPos1=0;
        endPos1=0;

        text=""; //  For New Translation  
        morseCode="";
        Serial.println("\n\nEnter Your Morse Code Here ");
       
             
        break;

        case 50: // 50 is Ascii value of 2
       
        morseCode.concat("@");
        Serial.print("@");
        delay(200);
       
        break;

        case 51: // 51 is Ascii value of 3
         
        morseCode.concat("#");
        Serial.print("#");
        delay(200);
       
        break;
       
      }
     
}

process();

}

void turnONLedSpeaker()
{
  //Turn ON LED
  digitalWrite(ledPin, HIGH);
  tone(speakerPin, 4699, 300); // tone(speakerPin, frequency, duration in milliSec)
 
}

void process()
{
 
  dotButtonState=digitalRead(dotButton);
dashButtonState=digitalRead(dashButton);




  if(dashButtonState == HIGH)
  {
    turnONLedSpeaker();
   
    morseCode.concat("-"); // Storing code in variable morseCode with the help of concatenation function
    Serial.print("-");//Prints User entered Code
    delay(200);
  }
  else if(dotButtonState == HIGH)
  {
   turnONLedSpeaker();
 
   morseCode.concat(".");
   Serial.print(".");
   delay(200);
   
  }
  else
  {
    //Turn OFF LED
    digitalWrite(ledPin, LOW);
     
  }

}

char convertIntoText(String characterCode)
{
  characterAscii=65;
 
  for(int index=0; index<SIZE; index++)
  {
    if(characterCode == letters[index])
    {
      return characterAscii;  
    }
    characterAscii++;  
  }

}

void extractLetters(String words)
{
        words.concat('@'); // Placeing @ at the end of word to simplify further processing

        endPos=words.indexOf('@');

       
        //Loop to extracting single character morse Code from string of word        
        while( endPos<words.length() )
       {
         characterCode=words.substring(startPos, endPos);
         
         //Now CharacterCode will now convert in text

         text.concat(convertIntoText(characterCode));
         
         startPos=endPos+1;
         characterCode="";
         
          // if condition is just to terminate loop when our extracting single character code is complete thats all
         if(startPos == words.length() )
         {
           break;
         }
         
         endPos=words.indexOf('@', startPos);  
       
       }
               
       
        Serial.print(text);
        Serial.print(" ");
        startPos=0;
        endPos=0;
        text="";    
 
}














