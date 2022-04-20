# Op Amp Tester

<img src="OpAmpTester.jpg" style="float:right">

This is a circuit that tests op amp chips to verify that they are working properly. You might find it useful if you repair old equipment, or if your prototype ciruits don't always work the way you expect. 🔥😕

### Features

- Tests single, dual, and quad op amp chips that have the standard DIP pinout
- LEDs blinking = op amps working!
- Powered by a 9-volt battery

### Usage

The circuit board has separate sockets for single, dual, and quad op amp chips. To test a chip, insert it in the appropriate socket and plug in a 9-volt battery. The LED(s) next to the chip should start blinking. If one or more of the LEDs don't blink, the chip is bad.

### Notes

This circuit should work with just about any DIP op amp chip (single, dual, or quad) that can operate on a 9 volt power supply and that has the usual pinout. I have tried it with several chips including:
- TL071, TL074
- LM358
- OPA2134

The PCB layout is provided in KiCad and gerber formats. (TBD) The PCBs that I used can be ordered from OSH Park. The design is [here.](https://oshpark.com/shared_projects/zzz)

Please note that I am a hobbyist, not a trained electronics engineer. No guarantees!

### References

This design is based on some other op amp testers that I found:

- [Edison Science Corner](https://www.youtube.com/watch?v=aGswFkS5oHQ)  
- [NightFire Electronics](https://vakits.com/single-op-amp-tester-kit)  
- [Synthchaser](https://synthchaser.com/product/synthchaser-op-amp-tester/)  

### Software Used

[KiCad](https://www.kicad.org/) 6.0.4

<hr /><div><div style="float:left; padding-right:10px;"><img src="https://i0.wp.com/www.oshwa.org/wp-content/uploads/2014/03/oshw-logo-100-px.png" width=71 height=75 /></div><div style="xfloat:left; padding-left:10px;"><a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0;" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />© 2022 Len Popp CC BY<br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.</div></div>