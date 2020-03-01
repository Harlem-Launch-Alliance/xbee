# xbee
X-Bee Pro S38 Real-Time Telemetry

X-Bee is a family of rf-based components created by Digi that are used for various projects, including rocketry. You can find out more information about the ecosystem here:
<br/>https://www.digi.com/xbee

It's expected that the HLA Messenger and Aries projects will ultimately use XBee hardware for their on-board-to-ground communications. The HLA org has at least 5 XBee Pro S38 components. Consider this: without real-time telemetry, a lot of stuff, including location data, is simply not available

In order to accomplish this, we need to read this document: 
<br/>https://www.digi.com/resources/documentation/digidocs/pdfs/90001496.pdf

The TLDR version is:
1) Download and Install XCTU:
<br/>https://www.digi.com/products/embedded-systems/digi-xbee/digi-xbee-tools/xctu

2) Download the Programmable XBee-Pro SDK, I found a copy here:
<br/>https://www.digi.com/resources/documentation/Digidocs/90002126/concepts/c_programmable_xbee_sdk.htm?tocpath=Hardware%7C_____5
<br/>(please let me know if this is no longer active)

3) To use UART serial communication with an Arduino or similar microcontroller, take a look at this document as well:
<br/>https://www.digi.com/resources/documentation/digidocs/90002173/Default.htm

4) show us a thing or two, you're in the lead!
