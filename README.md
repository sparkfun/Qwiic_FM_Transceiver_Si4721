# Qwiic FM Transceiver - Si4721

![Qwiic FM Transceiver](https://cdn.sparkfun.com//assets/parts/1/4/4/8/7/15853-Qwiic_FM_Transceiver_-_Si4721-02.jpg)

[*Qwiic FM Transceiver - Si4721 (SPX-15853)*](https://www.sparkfun.com/products/15853)

You're probably already familiar with Silicon Labs' brilliant 47xx line of radio devices. We've been carrying their FM tuners for a long time and find them reliable and simple to operate. That said, we thought it would be nice if you could _transmit_ as well as _receive_, so we looked into it and we found this excellent FM Transceiver!

The Si4721 integrates the complete tuner and transmit functions from previous Si47xx devices into one chip for both FM broadcast reception and standards-compliant*, unlicensed FM broadcast stereo transmission. On top of stereo audio the Si4721 will also transmit and receive RDS/RBDS, allowing you to send and receive strings of text on the FM Band. This is the same technology that modern commercial stations use to broadcast things like call signs and song names but we think you could have fun using it to broadcast sensor data or other arbitrary text data.

In order to be compliant with most broadcast regulations, this transmitter is extremely low power and has a reliable range of maybe 10 to 20 meters. These types of transmitters are most often found in things like intercoms or car stereo audio input adapters. Within range, however, the audio signal is extremely clear. 

The Qwiic FM Transceiver board includes not only the Si4721 IC but also a 3.5mm audio jack for line level input, a 3.5mm audio jack providing headphone level output via the on-board TPA6111 headphone amp, and a two position poke-home connector for easy antenna connection. The I²C address is jumper configurable between 0x11 and 0x63, allowing for multiple radio boards on a single Qwiic bus.

*In many parts of the world, using extremely low-power transmitters in the FM band for non-commercial purposes requires no license but you should always check the local laws just in case! <b>You are responsible for complying with local RF transmission regulations.
  
  Repository Contents
-------------------
* **/Hardware** - Eagle design files (.brd, .sch)

Documentation
--------------
* **[Arduino Radio Library](https://cdn.sparkfun.com/assets/f/2/a/3/6/Radio.zip)** - This is an archived (.zip) fork of the [Radio](https://github.com/mathertel/Radio) library with added Si4721 support and example code. 

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support through the [SparkFun forum](https://forum.sparkfun.com/index.php).

Please use, reuse, and modify these files as you see fit. Please maintain attribution to SparkFun Electronics and release any derivative under the same license.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
