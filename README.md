# group13-hw-ID-FourierSerious
Group 13 repository for the ID homework of CMLS 2022

# Group FourierSerious - Components:
- Manuel Alejandro Jaramillo Rodríguez
- Marcello Grati
- Maria Gracia Fernandez
- Silvia Pasin
- Natasa Popovic

# Project description:


# Instructions:
In order to use the plugin, you need to:
1. download the code
2. open the file "SubSynth.jucer" in Projucer
3. open it with an IDE (for example Xcode, Visual Studio..)
4. build the project inside the IDE
5. use the plugin in a music software


# Controls and Interface:

![GUI](https://github.com/polimi-cmls-22/group13-hw-ID-FourierSerious/blob/main/GUI.jpg?raw=true)

First of all, the spaceship moves freely through the interface to escape from the bullets thrown by the piano. Its movement will be done through the joystick both in its X and Y axis; however, performing these actions not only moves the ship, but also allows us to play with other parameters of our system. When we move on the X axis (analogX) we will control the cutoff frequency of the filter we have at that moment. Meanwhile, with the Y axis (analogY) we can change the type of filter so that, when the spaceship goes up it will correspond to a high pass filter, in the middle it will be a band pass filter and, if it is the farthest away from the piano, it will be a low pass filter.
      It should be noted that the frequency that is controlled with the analogX is mapped logarithmically. That is, the relationship between the range of joystick values (from 0 to 1) and the filter cutoff frequency range (from 65Hz to 523Hz), will be logarithmic in order to obtain a higher resolution in the low frequencies.
      On the other hand, through the conductivity switch sensor we will be able to vary the oscillator waveform. You can choose between sine, saw, square, triangle and white noise while continuing to control the ship, so that we can look for a better sonority while continuing to dodge bullets, giving rise to another challenge for the player.
      The score obtained is based on the number of bullets dodged, and is recorded and displayed to the player in the lower left corner of the screen along with the rest of the parameters mentioned above.


