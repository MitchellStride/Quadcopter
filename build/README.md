# Build

## Purpose
To build my own quadcopter because it will be fun to make and fly. It will serve
 as a low cost entry to the hobby and when I crash it, I will be able to fix it because I made it.
 <br>I am also hoping to add future functionality such as a mount for a recording
 camera or maybe a small claw.

## Acronyms
<ul>
  <li>ESC - Electronic Speed Control</li>
  <li>FC - Flight Controller</li>
  <li>PDB - Power Distribution Board</li>
  <li>FPV - First Person View</li>
  <li>VTX - Video Transmitter</li>
  <li>RX - Receiver</li>
</ul>

## BOM
#### Build

Category | Part
------------- | -------------
Frame | <a href="https://goo.gl/aYbrOu">LS-210</a>
Motors | <a href="https://goo.gl/a0K6uP">Racerstar 2205 BR2205</a>
ESC | <a href="https://goo.gl/fn3qAT">Racerstar RS20Ax4 20A</a>
FC | <a href="https://goo.gl/iR5tkF">F3 Acro 6 DOF</a>
PDB | <a href="https://goo.gl/FTEg89">Matek Systems PDB</a>
FPV Cam | <a href="https://goo.gl/6sQSpP">Eachine 1000TVL 110 Degree 2.8mm Mini</a>
VTX | <a href="https://goo.gl/18OOai">TS5823S Micro</a>
Antenna | <a href="https://goo.gl/7077TR">DYS FPV 5.8G 4dBi</a>
Propellors | <a href="https://goo.gl/aBQx3v">Dalprop Cyclone T5046C 5x4.6</a>

#### Accessories

Category | Part
------------- | -------------
VRX | <a href="https://goo.gl/d5XNC0">Eachine RC832</a>
Battery | <a href="https://goo.gl/b7iOPu">Infinity 4S 14.8V 1300mAh 70C</a>
Transmitter | Spektrum DX4 (Pre-Owned)
Receiver | <a href="https://goo.gl/u8BMjC">Redcon 2.4G DSM2 DSMX Satellite Receiver</a>
Battery Strap | <a href="https://goo.gl/LWe5i8">AKKU Tie Down Strap</a>
Antenna Extension | <a href="https://goo.gl/sd0MD9">60mm Extender</a>


## Plan
I have done some research on popular parts for cheap first quadcopter builds
and decided on these parts.
<br>
<img src="{{ "/pictures/blockcopter.png?raw=true" | prepend: site.baseurl }}" />
<br>This block diagram is how I am going to solder together the quadcopter. The three
main PCBs in the middle are called the "stack". Mine consists of a Racerstar 4in1 ESC,
Matek Power Board, and a F3 Flight controller. They will be fixated to the frame with
standoffs. The receiver will be under the Stack. The camera will be mounted to the front
with a wire leading to the VTX in the back.

## Build
<img src="{{ "/pictures/parts1.jpg?raw=true" | prepend: site.baseurl }}" />
<br>Now that I have recieved all the parts in the mail I soldered all the connections
as per the block diagram I made. I just planned out the wiring routing slowly as I went
and everything worked out perfectly.
<p>Once assembled, the software of the quadcopter is the last step. Plugging the Mini
usb port on the FC to my computer, it can be configured with BetaFlight.</p>
<img src="{{ "/pictures/Quad02.jpg?raw=true" | prepend: site.baseurl }}" />
<img src="{{ "/pictures/fullload.jpg?raw=true" | prepend: site.baseurl }}" />

## First Flight
Video of the first test flight.
<div style="position:relative;height:0;padding-bottom:56.25%"><iframe src="https://www.youtube.com/embed/0Ra9LfqjwCk?rel=0?ecver=2" width="640" height="360" frameborder="0" style="position:absolute;width:100%;height:100%;left:0" allowfullscreen></iframe></div>
<br>
More footage will come once I record it.

<br><a href="http://mitchellstride.com/Quadcopter">BACK</a>  
<br><a href="http://mitchellstride.com/">HOME</a>
