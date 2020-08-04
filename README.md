# TTGO T-Beam Range tester

Flash one device as Sender, one as Receiver. Screen will show signal strength and counter value of last packet received (value should always be in sync).

If desired, add a piezo buzzer on pin2, which will beep when a packet is received (currently every 10s).

Based on https://github.com/LilyGO/TTGO-T-Beam and https://www.youtube.com/watch?v=xrOo5SROzD8

Changes from LilyGO Original:
 - Changed band from 868E6 to 915E6 for US
 - SetTxPower to 20
 - SetSpreadingFactor to 12
 - Added EasyBuzzer.h for pin2 on receiver (easier to know whether transmissions are succeeding while driving)

![image](https://github.com/LilyGO/TTGO-T-Beam/blob/master/images/image1.jpg)

