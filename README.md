# attiny_midi_pitchbend
MIDI pitch bending wheel utilizing an attiny85
uses SoftwareSerial library for the MIDI control.

this specific program is for the use of just a single potentiometer. the one I am using uses a spring to return to center, though one can use a regular potentiometer. the code here calibrates the potentiometer and introduces a "dead zone" to make sure the pitch doesnt shift while in the center position. 

I am using a wheel ripped from a synthesizer, which utilizes a center tapped potentiometer, but for my case I do not need to use the center tap, as the software takes care of the need for a physical dead zone. it is also easier to program...

the build otherwise is very simple, following MIDI spec guidelines, I am personally using a 5 pin midi out. 

# todo for the future:
- make this battery powered
- switch to add modulation state
- indicator LEDs

all the schematics will be avaliable in the schematics folder, I do plan on producing PCBs for this device if it works well.
all will be housed in a guitar pedal blank, size to be determined. 
