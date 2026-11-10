This is a collection of files you will need to flash on to the ECU etc.

There is a XDF Definition file that works in TunerPro free for playing with whatever tables you want - with engish translated table descriptions.

A stock dump file to use as a basis.

My stock power, stock injector, stock turbo - slightly modified file that deletes stuff like evap, unwanted comms stuff, bypass valve etc - and most importantly it runs on the MR2 returnless fuel system with perfect fueling stratergy.

And lastly a file that runs on Bosch 550cc injectors with a slight boost in torque/power to give you a little more fun!

Tools you will need:-

1) Some sort of cheap USB to KKL OBD2 lead interface.
2) Nefmoto ME7 Flash Tool https://github.com/NefMoto/NefMotoOpenSource/releases/tag/v1.9.8.6
3) TunerPro free https://www.tunerpro.net/downloads.html
4) Tunerpro XDF definition translated to English = 8N0906018H__360313_english.xdf
5) ME7Sum = command line checksum correction tool if you want to modify the maps https://github.com/nyetlabs/ME7Sum/blob/master/ME7Check.exe
6) VisualME7Logger = https://github.com/sbloom82/VisualME7Logger/releases/tag/v2018.07.02.28
7) Logger memory definition file translate to english = N0906018H_Logdef_english.ECU

To delete/bypass the Immo on the ME7.5 Ecu you need to modify the EEPROM Data, this is a little 8 pin chip on the back of the ECU.

