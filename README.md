# ms404_reverse_pot_adapter
 a simple pcb to allow mounting modern potentiometers in the doepfer ms404 e.g. bournes pdb181 series and alpha rv16af series pots.

You can mix and match them with the original potentiometers, but I recommend changing them all, the original radiohm PCB mount pots are not a good design and cause the PCB to flex too much causing bad solder joints and damaged traces.

the ms404 service manual is here:

https://www.doepfer.de/ms404_sm.htm



1. dissasemble the ms404 and desolder the old potentiometers, the pot values are written on the PCB Except for the filter resonance potentiometer(that's the only antilog pot). check and reflow/bridge any bad connections on the ms404 PCB.

2. add bridge wires in the places where the pot chassis was acting as a jumper for GND. this is important, without bridge wires the ms404 will not work.

3. solder some long square pin headers in the PCB, 

4. fit the potentiometers to the front panel. the feet should be pointing up.

5. partially reassemble the ms404, everything except for the top panel,this will insure proper alignment of the pots.

6. place the adapter PCBs on the legs of the potentiometers and pin headers and solder them in , cut off any excess from the pin headers. make sure you leave a gap at the front between the adapter PCBs and the front panel. this is where the top panel fits.

I recommend you fit one to see how it works first before doing them all.


be careful when ordering PCB from random gerbers you find on the internet, the risk is all yours, I can only guarantee that they worked for me.