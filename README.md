# xbee
X-Bee Pro S38 Real-Time Telemetry Project

Please take all this info with a grain of salt. We are still in the early discovery phase.

X-Bee is a family of rf-based components created by Digi that are used for various projects, including rocketry. The HLA org has several XBee Pro S38 modules that may be utilized for development and/or testing. It's expected that the HLA Messenger and Aries projects will ultimately use XBee hardware for their on-board-to-ground communications. Without real-time communication between the rocket and ground crew, numerous useful data-points (for example, location data) remain unavailable. 

You can find out more information about the ecosystem here:
<br/>https://www.digi.com/xbee

Start by taking a look at this document: 
<br/>https://www.digi.com/resources/documentation/digidocs/pdfs/90001496.pdf

The TLDR version is:
1) Download and Install XCTU:
<br/>https://www.digi.com/products/embedded-systems/digi-xbee/digi-xbee-tools/xctu

2) Download and install Code Warrior v10.2
<br/>http://ftp1.digi.com/support/sampleapplications/40003004_B.exe

2) Download the Programmable XBee-Pro SDK, I found a copy here:
<br/>https://www.digi.com/resources/documentation/Digidocs/90002126/concepts/c_programmable_xbee_sdk.htm?tocpath=Hardware%7C_____5
<br/>(please let me know if this is no longer active)

3) To use UART serial communication with an Arduino or similar microcontroller, take a look at this document as well:
<br/>https://www.digi.com/resources/documentation/digidocs/90002173/Default.htm

3/2/2020:
We've made some progress towards setting up a priliminary network today using 2 XBee Pro S3Bs connected to my laptop. See the XSC DigiMesh 2.4 Getting Started Guide, pg. 15-17 for details. 
