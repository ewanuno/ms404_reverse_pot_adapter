# ms404_reverse_pot_adapter
 a simple pcb adapter to allow mounting modern potentiometers in the doepfer ms404 e.g. bournes pdb181 series and alpha rv16af series pots.






You can mix and match them with the original potentiometers, but I recommend changing them all, the original radiohm PCB mount pots are not a good design and cause the PCB to flex too much causing bad solder joints and damaged traces.

the ms404 service manual is here:

https://www.doepfer.de/ms404_sm.htm

![installed](https://github.com/ewanuno/ms404_reverse_pot_adapter/assets/2670261/23c207a9-397c-4d81-b1ab-e9c9c5c6671b)


1. dissasemble the ms404 and desolder the old potentiometers, the pot values are written on the PCB Except for the filter resonance potentiometer(that's the only antilog pot). check and reflow/bridge any bad connections on the ms404 PCB.

2. add bridge wires in the places where the pot chassis was acting as a jumper for GND. this is important, without bridge wires the ms404 will not work.
  on most of the potentiometers it is only nessascary to add bridge wire to the sides, but on at least one of them it is also nessacary to add awire on the front. the person who designed the PCB used the metal body of the potentiometer to connect Gnds on the the pcb in many places, since our new potentiometers don't have these pins, we need to add wires in the appropriate places, thankfully these are marked on the pcb silkscreen.

3. solder some long square pin headers in the PCB, they need to be long enough to reach fron the ms404 to the adapter pcb, so they need to be at least 36mm long.

4. fit the potentiometers to the front panel. the feet should be pointing up.

5. partially reassemble the ms404, everything except for the top panel,this will insure proper alignment of the pots.

6. place the adapter PCBs on the legs of the potentiometers and pin headers and solder them in , cut off any excess from the pin headers. make sure you leave a gap at the front between the adapter PCBs and the front panel. this is where the top panel fits.

I recommend you fit one to see how it works first before doing them all.
![ms404 front panel](https://github.com/ewanuno/ms404_reverse_pot_adapter/assets/2670261/08e6c631-36a3-4801-b6ce-9d074a52e05d)

![pcbs](https://github.com/ewanuno/ms404_reverse_pot_adapter/assets/2670261/7180b27d-72d4-4c21-b4a7-74ffcf86cc7b)

be careful when ordering PCB from random gerbers you find on the internet, the risk is all yours, I can only guarantee that they worked for me. i had them made at jlcpcb.
