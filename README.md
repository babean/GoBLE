# GoBLE

A Particle port of DFRobot's library for GoBLE
https://www.dfrobot.com/wiki/index.php/Bluetooth_APP_Control

This enables the uses of genertic BLE modules like HM-10 with Particle for added RC control.

Using AT commands, set the HM-10 as follows (all other settings at default values):

AT+BAUD4

AT+UUID0xDFB0

AT+CHAR0xDFB1

Then connect hm-10's TX to Particle Serial1_RX, connect power. Good to go.

