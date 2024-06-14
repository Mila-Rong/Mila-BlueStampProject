# Posture Corrector
Ever wondered how mastering good posture can transform your confidence and presence? Cleveland clinic states that standing and sitting up straight can boost confidence and reduced risk of injury. 
My project is aim to help people to correct sitting posture and remind them anytime.
What sets this project apart is the incorporation of numerous innovative features.
At first I...
These experiences have significantly enhanced my problem-solving skills.

Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Mila R. | Saratoga High School | Engineering | Incoming Sophomore

[Headstone Image](BlueStampSelfImage.png)

(https://github.com/Mila-Rong/Mila-BlueStampProject/assets/172335758/15034bd9-d609-4934-9548-9146c88ba177)
(https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**
  
<!---# Final Milestone
# Second Milestone-->
# First Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/qWUt8Wl382Y?si=09idMhwT-X0u8iI2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

My first mile stone is to complete the flex sensor connection, program the arduino with required code and make sure the flex sensor works. My first step is to make images of WS2812b led strip and flex sensor schematics. After solding wires and connecting, I programed code. First, I wrote a if sentence to accomplish the LED stripe real time turn red when the flex sencor bend over an expected critical value; Turn green sequentially when the flex sensor is less than expected value. With the help of Adafruit_NeoPixel library and a for loop, the computer can control color, brightness, LED amount and time to turn on of the LEDs.
One challenge that I had for this milestone was the LED was always red when the value represents flex sensor bend degree is 0. It's because the else sentence isn't excuted. I didn’t get to know well the Adafruit_NeoPixel library dictionary, so I omissioned the strip.show() that refresh the display for these changes to take effect.
My next step is to enable the project connection with a Android phone program to have a higher degree of completion.
# Schematics 
WS2812b LED Strip
![Shiny Bruticus](https://github.com/Mila-Rong/Mila-BlueStampProject/assets/172335758/806cf273-35f5-4d4e-9e75-c705c9f0e79d)
Flex sensor
![image](https://github.com/Mila-Rong/Mila-BlueStampProject/assets/172335758/84bef1d8-1d6a-4011-be44-0f94c5fc4af5)
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser.
# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino Uno | Open source microcontroller used to read inputs | $28.50  | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/ref=sr_1_3?crid=3VNEAL981J2CL&keywords=arduino+uno&qid=1685848547&sprefix=arduino%2Caps%2C170&sr=8-3"> Link </a> |
|:--:|:--:|:--:|:--:|
| Breadboard | Used to build circuts | $5.99 | <a href="https://www.amazon.com/Qunqi-point-Experiment-Breadboard-5-5%C3%978-2%C3%970-85cm/dp/B0135IQ0ZC/ref=sr_1_10?crid=2NREO3D61OYUY&keywords=breadboard&qid=1687992200&sprefix=breadboar%2Caps%2C210&sr=8-10"> Link </a> |
|:--:|:--:|:--:|:--:|
| LED Lights | Used to alert the user that they are in bad posture | $34.95 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Yoga Ball | The user sits on this yoga ball | $24.95 | <a href="https://www.amazon.com/OPTP-Soft-Movement-Ball-Stability/dp/B07HZ1ZF2M/ref=sr_1_6?crid=2Z3VMANLO7K39&keywords=pilates+yoga+ball+12+inches&qid=1687561381&sprefix=pilates+yoga+ball+12+inche%2Caps%2C146&sr=8-6"> Link </a> |
|:--:|:--:|:--:|:--:|
| Jumper Wires Male | Connection source from arduino to breadboard | $1.95 | <a href="https://www.adafruit.com/product/1950"> Link </a> |
|:--:|:--:|:--:|:--:|
| Solid Core Wire | Connection source from arduino to breadboard and LED strip | $2.95 | <a href="https://www.adafruit.com/product/290"> Link </a> |
|:--:|:--:|:--:|:--:|
| Power Source | External powersource to power the arduino and the LED strips | $7.19 | <a href="https://www.amazon.com/Arkare-100V-240V-Replacement-Security-Raspberry-Pi/dp/B09W8X9VGK/ref=sr_1_2?keywords=ac+dc+adapter+5v&qid=1687987358&sr=8-2"> Link </a> |
|:--:|:--:|:--:|:--:|
| Long Flex Sensor | Sensor used to measure the resistance of the user. | $12.95 | <a href="https://www.adafruit.com/product/182"> Link </a> |
|:--:|:--:|:--:|:--:|
| 10K Ohms Resistor | Used to generate values for the flex sensor  | $0.75 | <a href="https://www.adafruit.com/product/2784"> Link </a> |
|:--:|:--:|:--:|:--:|
| Secrew Terminal Barrel Jack | Used to connect breadboard to external power source  | $7.49 | <a href="https://www.adafruit.com/product/2784](https://www.amazon.com/CGTime-Adapter-terminals-Connector-Security/dp/B07LFRDSB7/ref=sr_1_4?crid=2932T6C3FL0FF&keywords=screw+terminal+barrel+jack&qid=1688745780&sprefix=screw+termianl+barrel+jack%2Caps%2C142&sr=8-4)"> Link </a> |
|:--:|:--:|:--:|:--:|
| Android | Used to control the app and receive notifications  | $159.99 | <a href="https://www.amazon.com/dp/B09MZBTMQQ/ref=twister_B0BTCN5QXV?_encoding=UTF8&psc=1"> Link </a> |
|:--:|:--:|:--:|:--:|
| Bluetooth Terminal | Used to send data wirelessly to app  | $9.99| <a href="https://www.amazon.com/DSD-TECH-HC-05-Pass-through-Communication/dp/B01G9KSAF6/ref=sr_1_3?crid=1YJUU51AP8LFK&keywords=hc05+bluetooth+module+for+arduino&qid=1688745485&sprefix=HC05+blueetoo%2Caps%2C158&sr=8-3"> Link </a> |
|:--:|:--:|:--:|:--:|

# Starter Project: Arduino Starter
<iframe width="560" height="315" src="https://www.youtube.com/embed/AmasHNNt3hI?si=7HS6WkTH1lH-Cv-b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
For my starter project, I built a Arduino starter that has ability to detect whether there is an object in front and the distance from itself. This happens by using an ultrasounic sensor and LED. To measure the realtime distance, it will time the ultrasound emmited travel back and forth from the object. The ultrasound velocity is known as 340m/s, allow it to calculate the the distance(S = vt), and shown through serial monitor. To control the LED turn on when the object is near, Arduino IDE is utilized to add code and ensure the LED turn on when the distance is less than 6cm, off when the distance is greater than 6cm.
The main challenge I met is that the LED is always on. What I did first is to change the digital write order from the critical distance mistakely written to ledpin serial number. Besides, I found the sencer measure the distance as 0 if an object is farther than it max distance, such as when there is nothing. Finally, I add code about not turn LED on when the distance is 0. However, this project allowed me to become comfortable using Arduino systems and related tools.
[Headstone Image](Neat Kieran.png)
## Code
```
// Include NewPing Library
#include "NewPing.h"

// Hook up HC-SR04 with Trig to Arduino Pin 9, Echo to Arduino pin 10
#define TRIGGER_PIN 9
#define ECHO_PIN 10
// Maximum distance we want to ping for (in centimeters).
#define MAX_DISTANCE 1000000	

// NewPing setup of pins and maximum distance.
NewPing sonar(TRIGGER_PIN, ECHO_PIN, MAX_DISTANCE);

void setup() {
	Serial.begin(9600);//how fast it communicate
  const int ledPin = 13;//the ledPin is always Pin7
  pinMode(ledPin, OUTPUT);//the ledPin's job is always OUTPUT
}

void loop() {//Excute the order over and over again. Measure the distance between the ultranic senser ro the nearest object and determine whether to turn the LED on or not.
  int d = sonar.ping_cm();
  Serial.print("Distance = ");
	Serial.print(d);
	Serial.println(" cm");
  if (d < 6) {
    digitalWrite(13, 1);
  }
  if (d == 0){
    digitalWrite(13, 0);
  }
  else if (d > 6){
    digitalWrite(13, 0);
  }
  delay(100);
}
```
<!---# Other Sources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here. -->
