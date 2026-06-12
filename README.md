Audio amplifier project implementing the LM3886 audio power amplifier.
Originally intended to replace a busted board in a powered subwoofer, but designed to be reused as a L/R stereo amp.
NOTE: the mute circuit was incorrectly connected to ground instead of the negative rail. Current draw necessary to unmute cannot be achieved unless the switch is connected to the negative rail.
Realistically, not all three matching pairs of caps in the cap bank are necessary. Connect the mute switch to one of the negative rail through holes in the cap bank if the bank isn't fully populated.
The low voltage power components are also not necessary for function. They are there to power peripherals (indicator lights, add-on pre-filters or pre-amps, etc.)
