# 4x-Electric-Druid-ADSR-KOSMO (UN TESTED)
A kind of crude envelope generator based around the ENVGEN 8C chip from electric druid and LMNC's circuit for the mini ADSR

I originally designed this on stripboard which It's worked great since but after moving my modules around and debugging over 50+ wires for which one may have shorted I decided to make a PCB layout. The old stripboard layout works fine but It's ALOT of wired connections and 2 boards.
This is a PCB layout for a 4 envelope generators based around LMNC's ADSR and the electric druid chip ENV GEN 8C.
This has the a level knob added and it's 6 knobs ADSR time and level with a mode switch (ADSR, Gated loop and loop) and 16 jacks (a gate input, 2 output and a negative output for each envelope)
Theres a panel layout with the holes for everything except the LED's which I added after. I'm still using my old painted aluminum panel for this but The space for optional LEDs are on the Main PCB.
There's also holes on the panel that fit the Tayda stripboard mounting holes.
The LEDs are connected directly to the output so there may be some voltage drop but I've not noticed anything on the stripboard version
This module is untested the stripboard layout works

The files for the PCBs are all layed out in Kicad


UPDATE circuit has been verified and tested but there is a single missing trace for envelope 3
Between R27 and R49 be sure to a trace or jumper between those Reuploading the fixed board

The files on github have been updated with the missing trace, Everything should work as expected.
Added a BOM for both boards***


![Screenshot 2024-01-28 200758](https://github.com/ChurroLightyear/4x-Electric-Druid-ADSR-KOSMO/assets/545014/242cc3ee-8498-4798-bc47-4077bf43ada8)
