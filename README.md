# IR-for-LEDS
Send IR Codes from an Arduino to an RGB LED Strip
This is created by Star Prep Academy
This is currently still IN DEVELOPMENT. 
If support is needed, create a ticket in the issue section.


-- ABOUT THIS PROGRAM --
This program utilizes a default arduino IR library and one that can be downloaded on this git. It contains default patterns that you can use, by just calling them in a void loop. For Example:

void loop(){
basicpattern();
}

That code will run the LED pattern found in the library folder. You can also create your own patterns:
void loop(){
irsend.sendRaw(purple,68,38)
purple is the color
68 is the amount of digits in the string (68 is the most common number of digits)
38 is the frequency



-- COPYRIGHT / ACCEPTABLE USE / EULA --
You are free to change, redistrubute, copy, and use this code. Please do not claim it as your own. "this code" refers to everything found in this git hub directory, including, but not limited to, libraries, files uploaded, Arduino code, and responses to issues. 


-- CREDIT --
I owe credit to my Electronics teacher Walter, and my Tech-Lab teacher Dylan. Credit is also due to Star Prep Academy staff and students, some of which will be listed below.

All the students in the Tech Lab Class and Avery from Electronics. Credit also goes to Chase my math teacher, who helped with some ideas. Thanks to Thomas V., My history teacher, for letting me sit in his class during countless lunches working on this project. 
