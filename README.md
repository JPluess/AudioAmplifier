#This is a Low-Budget Audio (pre)-Amplifier with an LM358 /LMV358

Release Notes,

•	The audio input signal on the left side of the schematics is where you connect the audio source.

•	If you want to filter the low audio frequencies, use caps lower than 1uF, above 1uF it won’t make much of a difference. 

•	If you want to change the volume of the amp you change R7 or R8, remember the amplitude cannot go over the input voltage of 5V. It will result in a clipping sound. 

•	If you use LM358 and not LMV358 (Rail to Rail, 5,5V Max) the output swing of the LM358 is only to VCC-1.5V so 3.5V is all you get. I recommend using LMV358 since it can go almost to VCC.

•	The AGND and GND are supposed to be connected in star, which means over 1 Resistor at R19. Some suggest using about 10uH and a Capacitance. 

I use this schematic with success to amplify the audio signal from a Bluetooth chip like CSR8645 in order to match the amplitude to an average stereo signal. This I connected to a regular Logitech PC speaker input.  You can also use it for small headphones.

I am aware there are specific audio pre amps on the market.  

I am not a professional and share my insight in the hope to contribute to your success. Use my schematics at your own risk. If you know it better, feel free to send me a message. I am always glad to learn.

