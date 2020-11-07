# colour-detector-using-arduino-uno

The aim of the project is automation in industries. Colour is derived from the wavelength and intensity of light in the visible spectrum. Colour detection has a variety of application in industries, for example, a colour of products can be used as a quality control measure. In other words such as automobile, textile and paint industries, products and input materials can be shorted according to their colours with the help of colour detecting sensor.

Features of the colour detection machine are as follows:

- Detection of primary colours Red, blue and green.
- Showing accurate and real time result.
- Uses Low power for processing.

Structure and working -
- The TCS3200 colour sensor with Arduino UNO R3. The TCS3200 colour sensor measure three primary 
  colours red, blue, green and it also has a separate white light detector. Since any colour can be 
  created from different levels of this primary colours. The unit can tell you the colour composition of 
  a  light source.
-The four LEDs on the sensor board are there to illuminate the subjects with an even light source --- 
 making it easier to get a light measurement.
-The UNO here send a signal to the module to detect colours and the data received by the module is 
 shown in the 16*2 LCD connected to it. The UNO detects three-colour intensities separately and 
 shows them on LCD.

Technology used - Arduino UNO R3, TCS3200 colour sensor, 16x2 LCD module, breadboard, C, C++
