# ArduinoDrums
My code for an arduino based drumkit. There are two versions of the code: TimedDrums and InstaDrums. The first one plays a MIDI message through the USB with the maximum velocity found in the 5 milliseconds following the first hit, whereas InstaDrums immediately plays the note as the program detects the voltage input is decreasing. While this second version should be quicker, it is also more sensible to fluctuations.


Neither of the codes have been tested so far, the MIDI codes for the notes are not set to mean anything in particular, the threshold value(s) for the piezos have not been set in any sensible way. This code will be updated as soon as I can test it on a drum pad.
