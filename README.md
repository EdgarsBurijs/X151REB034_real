# Majaslappa
Source code

!DOCTYPE html>
<html>
<head>
<title>Webpage</title>
</head>

<body style="background-color:Black;">

<h1 style="color:green;">Welcome to the Pepe site!</h1>

<p style="color:green;">In this site you will find the rarest Pepe of all time.</p>

<p style="color:green;">GitHub ---> https://github.com/x151REB034/x151REB034.git </p>

<h2 style="color:green;">The history of Pepe the Frog.</h2>

<p style="color:green;">In 2005, artist Matt Furie created the comic series Boys Club, which stars the teenage monster character Pepe</p>

<h3 style="color:green;">One of the rarest Pepes of all time:</h3>

<img class="irc_mi" style="margin-top: 100px;" src="http://ih1.redbubble.net/image.92198960.2439/flat,800x800,075,t.jpg" width="400" height="400">

<img src="http://41.media.tumblr.com/4d555e4cb1232587c87477b6453c70a6/tumblr_nr3gwdHJc61rlvpheo1_500.jpg" alt="The Rarest Pepe." width="400">

<h4 style="color:green;"> Whant to see some gif?</h4>

<img class="post_media_photo image" alt="" width="540" height="540" style="width: 540px; height: 540px;" src="https://49.media.tumblr.com/6499232dbca6a8752392f551404fba82/tumblr_o0laqfLTWB1ubm73lo1$

<h5 style="color:green;"> How about some SVG?</h5>

<svg width="400" height="180">
  <rect x="50" y="20" rx="20" ry="20" width="150" height="150"
  style="fill:green;stroke:white;stroke-width:6;opacity:1"/>
</svg>

<svg width="300" height="200">
  <polygon points="100,10 40,198 190,78 10,78 160,198"
  style="fill:green;stroke:white;stroke-width:3;fill-rule:evenodd;" />
</svg>


<h6 style="color:green;">A place for resistor</h6>

<img src="//lh3.googleusercontent.com/-q2Ht1H8Z1wo/V0Ayq6ImfqI/AAAAAAAAABc/KEVn9evfCxUIE-LG2V_-J1-91w-imEzYACLcB/w506-h285/Resistor3D.png" class="ar Mc" style="max-height:285px; max-width:506px;" i$

<iframe width="560" height="315" src="https://www.youtube.com/embed/CjTi-dMDdpg" frameborder="0" allowfullscreen></iframe>

<h7 style='color:green;'>Dank Video --------------> </h7>



<iframe width="853" height="480" src="https://www.youtube.com/embed/JH3lyZYlERE" frameborder="0" allowfullscreen></iframe>

</html>

#Cuska
int PIN_SCE = 6;//SS
int PIN_RESET = 7;
int PIN_DC  = 5;// data
int PIN_SDIN = 4 ;//MOSI  SIMO
int PIN_SCLK =3 ;//CLK SCLK
int PIN_BL =9 ;//BL LED
int PIN_VCC =2 ;//Vcc +-

#define LCD_C LOW //command
#define LCD_D HIGH //data high command low.
#define LCD_X 84 ///character area //
#define LCD_Y 48  //consists of banks of 7 by eight pixels.//
#define LCD_DATA 1
const unsigned char nokia [] = {
    0x00, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0x80, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,
    0xE0, 0xE0, 0xE0, 0xE0, 0x00, 0x00, 0xC0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0,
    0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xC0, 0x80, 0x00, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0x00, 0x00, 0x00,
    0x00, 0x80, 0xC0, 0xE0, 0xE0, 0xE0, 0xE0, 0x60, 0x20, 0x00, 0x40, 0xE0, 0xE0, 0xE0, 0xE0, 0x00,
    0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0xC0, 0xE0, 0xE0, 0xE0, 0xE0, 0xE0, 0xC0, 0x00, 0x00, 0x00,
    0x00, 0x00, 0x00, 0x00, 0x00, 0xFF, 0xFF, 0xFF, 0xFF, 0x0F, 0x0F, 0x3F, 0xFF, 0xFF, 0xFE, 0xF8,
    0xF0, 0xC0, 0x00, 0x00, 0xFF, 0xFF, 0xFF, 0xFF, 0x00, 0xFE, 0xFF, 0xFF, 0xFF, 0xFF, 0x03, 0x03,
    0x03, 0x03, 0x03, 0x03, 0x03, 0x03, 0x03, 0xFF, 0xFF, 0xFF, 0xFF, 0x00, 0xFF, 0xFF, 0xFF, 0xFF,
    0xFF, 0xF0, 0xF8, 0xFC, 0xFE, 0xFF, 0xDF, 0x0F, 0x07, 0x03, 0x00, 0x00, 0x00, 0x00, 0xFC, 0xFF,
    0xFF, 0xFF, 0xFF, 0x00, 0x00, 0x00, 0x00, 0xE0, 0xF8, 0xFF, 0xFF, 0x7F, 0x1F, 0x07, 0x1F, 0xFF,
    0xFF, 0xFF, 0xF8, 0xE0, 0x00, 0x00, 0x00, 0x00, 0x00, 0xFF, 0xFF, 0xFF, 0xFF, 0x01, 0x00, 0x00,
    0x00, 0x01, 0x07, 0x1F, 0x7F, 0xFF, 0xFF, 0xFE, 0xFF, 0xFF, 0xFF, 0xFF, 0x00, 0x0F, 0x7F, 0xFF,
    0xFF, 0xFF, 0xF8, 0xF8, 0xF8, 0xF8, 0xF8, 0xF8, 0xF8, 0xF8, 0xF8, 0xFF, 0xFF, 0x7F, 0x1F, 0x00,
    0xFF, 0xFF, 0xFF, 0xFF, 0xFF, 0x00, 0x01, 0x03, 0x07, 0x1F, 0x3F, 0x7F, 0xFE, 0xFC, 0xF8, 0xF0,
    0xC0, 0x80, 0xF9, 0xFF, 0xFF, 0xFF, 0xFF, 0x00, 0xE0, 0xFC, 0xFF, 0xFF, 0x7F, 0x1F, 0x1F, 0x1F,
    0x1F, 0x1F, 0x1F, 0x1F, 0x1F, 0x1F, 0xFF, 0xFF, 0xFF, 0xFC, 0xE0, 0x00, 0x00, 0x00, 0xC0, 0xC0,
    0x40, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,
    0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x80, 0x00,
    0x00, 0x60, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,
    0x00, 0x00, 0xC0, 0xC0, 0xC0, 0x80, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,
    0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0xE0, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,
    0x00, 0xFF, 0xDF, 0x00, 0x00, 0xF0, 0xFE, 0x06, 0x06, 0xFE, 0x70, 0xFE, 0xFE, 0x06, 0x06, 0xFE,
    0x00, 0xFE, 0x1E, 0x02, 0x86, 0xFC, 0x00, 0xFC, 0x66, 0x62, 0x7E, 0x38, 0xF8, 0xFE, 0x06, 0x02,
    0x02, 0xFF, 0xFF, 0x02, 0x02, 0xFE, 0x00, 0x00, 0xFE, 0x06, 0x06, 0xFE, 0x00, 0xF8, 0xDE, 0x02,
    0x06, 0xFE, 0x00, 0x00, 0x00, 0x00, 0xFF, 0x60, 0x60, 0x3F, 0x00, 0xFC, 0x66, 0x62, 0x7E, 0x38,
    0xF8, 0xFE, 0x02, 0x06, 0xFC, 0x00, 0xFE, 0xFE, 0x02, 0x06, 0xFC, 0x00, 0xFF, 0x80, 0xF0, 0xFE,
    0x62, 0x66, 0x7C, 0x00, 0x00, 0x01, 0x07, 0x0C, 0x0C, 0x04, 0x07, 0x0C, 0x0C, 0x07, 0x00, 0x07,
    0x07, 0x00, 0x00, 0x07, 0x00, 0x07, 0x07, 0x00, 0x01, 0x07, 0x00, 0x07, 0x06, 0x0C, 0x0C, 0x00,
    0x01, 0x07, 0x0C, 0x0C, 0x00, 0x03, 0x0F, 0x0C, 0x04, 0x07, 0x00, 0x00, 0x07, 0x00, 0x00, 0x07,
    0x00, 0x03, 0x27, 0x2C, 0x2E, 0x3F, 0x00, 0x00, 0x00, 0x00, 0x07, 0x00, 0x00, 0x00, 0x00, 0x07,
    0x0E, 0x0C, 0x0C, 0x00, 0x01, 0x07, 0x0C, 0x0E, 0x07, 0x00, 0x3F, 0x1F, 0x0C, 0x06, 0x03, 0x00,
    0x07, 0x00, 0x00, 0x07, 0x0C, 0x0C, 0x04, 0x00,
};
void posmarker()  {
    LcdWrite( 0, 0x80|0);
    LcdWrite( 0, 0x40|0);
}
void pozicija(char x, char y)

{
    LcdWrite( 0, 0x80|x);
    LcdWrite( 0, 0x40|y);
}
void kursors(unsigned char z)
{
          digitalWrite(PIN_DC,HIGH);
        digitalWrite(PIN_SCE, LOW);
        //shiftOut(PIN_SDIN, PIN_SCLK, MSBFIRST,nokia[index3]);
        shiftOut(PIN_SDIN, PIN_SCLK, MSBFIRST,z);
        digitalWrite(PIN_SCE, HIGH);
}

void LcdClear(void) {
    for(int index = 0; index < 504; index++){
        LcdWrite(LCD_D, 0x00);
    }
}
void LcdWrite(byte dc, byte data) {
    digitalWrite(PIN_DC, dc);
    digitalWrite(PIN_SCE, LOW);
    shiftOut(PIN_SDIN, PIN_SCLK, MSBFIRST, data);
   digitalWrite(PIN_SCE, HIGH);
}
void initialise() {
    pinMode(PIN_VCC, OUTPUT);
    pinMode(PIN_SCE, OUTPUT);
    pinMode(PIN_RESET, OUTPUT);
    pinMode(PIN_DC, OUTPUT);
    pinMode(PIN_SDIN, OUTPUT);
    pinMode(PIN_SCLK, OUTPUT);
    pinMode(PIN_BL, OUTPUT);
    digitalWrite(PIN_VCC, HIGH);
    digitalWrite(PIN_RESET, LOW);
    digitalWrite(PIN_RESET, HIGH);
    LcdWrite(0, 0x21);
    //Tell LCD that extended commands follow
    LcdWrite(0, 0xB9);
    //Set LCD Vop (Contrast): Try 0xB1(good @ 3.3V) or 0xBF if your display is too dark
    LcdWrite(0, 0x04);
    //Set Temp coefficent
    LcdWrite(0, 0x14);
    //LCD bias mode 1:48: Try 0x13 or 0x14
    LcdWrite(0, 0x20);
    //We must send 0x20 before modifying the display control mode
    LcdWrite(0, 0x0C);
    //Set display control, normal mode. 0x0D for inverse
    //digitalWrite(PIN_BL, HIGH);
}
void setup()  {
    initialise();
    LcdClear();
    posmarker();
}
void loop(){
    pozicija(0,0);
    for (int index3 = 0; index3 < 84; index3++) {
        digitalWrite(PIN_DC,HIGH);
        digitalWrite(PIN_SCE, LOW);
        //shiftOut(PIN_SDIN, PIN_SCLK, MSBFIRST,nokia[index3]);
        shiftOut(PIN_SDIN, PIN_SCLK, MSBFIRST,0xFF);
        digitalWrite(PIN_SCE, HIGH);
    }
     pozicija(0,5);
    for (int index3 = 0; index3 < 84; index3++) {
        digitalWrite(PIN_DC,HIGH);
       digitalWrite(PIN_SCE, LOW);
        //shiftOut(PIN_SDIN, PIN_SCLK, MSBFIRST,nokia[index3]);
        shiftOut(PIN_SDIN, PIN_SCLK, MSBFIRST,0xFF);
        digitalWrite(PIN_SCE, HIGH);
    }


    for (int index3 = 0; index3 < 6; index3++) {
      pozicija(83,index3);
      kursors(0xFF);
    }
    for (int index3 = 0; index3 < 84; index3++) {
      pozicija(index3,2);
      kursors(0xFF);//uzzimesana
      delay(200);
      pozicija(index3,2);
      kursors(0x01);//dzesana
      pozicija(index3,2);
      kursors(0x84);//uzzimesana
      }

      for (int index3 = 84; index3 > 0; index3++) {
   pozicija(index3,2);
      kursors(0xFF);//uzzimesana
      delay(200);
      pozicija(index3,2);
      kursors(0x01);//dzesana
      }

    delay(2000);
}




