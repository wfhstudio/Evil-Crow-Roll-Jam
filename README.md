# Evil-Crow-Roll-Jam
The firmwares are created by h-RAT Thanks to him
Provided Gerber files to tidy up the project but somehow, the wiring is not good, so I fixed with adding more cable back and front sides as show in the Picture. You can also do the wiring by yourselves using the provide wiring guideline.

This Project using 2 x ESP 32: 1 is for Rolling device and the other one is for Jam device . Jam device is connected to Rolling device through IP address. The IP then configured in Rolling device by inputting through the browser.

How to configure Jam IP address:
Connect to SSID : ECRF password: 123456789
Menu: ECRF Setting
Go down and Find Jammer Device then put the IP address

Note:
For simplycity you can use jammer firmware zip file: 2xCC1101_JAMMER_WORK_ESP32. This is set for 433.75 (you still can change the frequency in the ino file). No need IP address to connect.

Demo: https://www.youtube.com/watch?v=3oUOgmfth70&t=72s&ab_channel=WorkFromHome2021
