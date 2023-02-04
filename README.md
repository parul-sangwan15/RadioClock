# RadioClock
 Receive and interpret a  Rugby Clock Signal
INTRODUCTION
• The MSF signal, also known as the Rugby Clock signal, is a radio signal sent out by 
the National Physics Laboratory in Anthorn, United Kingdom. It displays the current 
time and date in Coordinated Universal Time (UTC) (UTC). 
• The goal of this project is to use CMOS 4000 series ICs to receive and interpret a 
Rugby Clock Signal. This signal is broadcast at 60 kHz and is keyed ON/OFF. 
• Due to the unreliability of the wireless medium, we were given a PIC microcontroller 
to create the MSF signal throughout the development stage.
• The pins considered on this chip can be directly attached to our circuit for final 
testing.
• For the schematic design, we were asked to use counters for seconds and design 
further logic for minutes and hours, given minutes marker codes.
• Once the logic part of the circuit is finished, it was built and tested on the breadboard 
as well followed by some difference in multisim schematic and manual building of 
the circuit.
• The circuit was expected to provide a display of hours, minutes and seconds 
[23:59:59] using 7 segment displays.
