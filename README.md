# IC-TESTER
I just created an ic tester in c/c++ using arduinio with nokia lcd or you can use 16by2  i2c or any other.
Basically thir are two features of this ic tester
one is to search which ic is this
and second is which gate of this ic working and which not
basically i added 6 ic's in this code later on i will add some more ic to be tested 
those ic's that can be tested are given below
AND
NAND
XOR
OR
NOR
NOT
librarires i am using are
if you are using 16 by 2 lcd then you have to add LiquidCrystal.h
if you are using nokia 5110 lcd as i am using this then you have to add NOKIA_5110
if you are using 16by2 i2c then you have to use LiquidCrystal_I2C.h
the arduino i am using is mega 2560 you can use mega ADK but it expensive or you can use UNO which perfectly fit for htis project
if you want to use arduino UNO then you have to replace the below given pins 
const int pin_9 =  34;replace 34 with 14
const int pin_10 = 32;replace 32 with 13
const int pin_11 = 30;replace 30 with 12
const int pin_12 = 28;replace 28 with 11
const int pin_13 = 26;replace 26 with 9
const int pin_14 = 24;replace 24 with 8
const int pin_15 = 22;replace 22 with 7
const int pin_16 = 36;//vcc  directly attach it to vcc+5v
you will need 24 male to female connecting wires
MOST IMPORTANT is that the simulator that i am using is PROTEUS PRODESSIONAL 8 and i sugest you as well
you can directly give the nokia lcd ground or vcc from arduino or just like me from pin giving high and low signal for vcc and ground respectively
You can mail me if any problem occur 
given .ino if the arduino file 
above .pdsprj is the protues file
above .hex file is use for the arduino in proteus 
circuit diagram is given iin screenshot given above you can change the pins by changing a little bit in code
