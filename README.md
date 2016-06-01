# Tiny-Genius
This little project uses an ATTiny85 to make a Simon Says (Genius, in Brazil) game clone. The trick here is that, due to the I/O limitations of the Tiny, all the pushbuttons are read in a single analogIn port, according to the resistor attached to it. Each resistor implies in a different analogRead() value, which is used in a switch/case later.
