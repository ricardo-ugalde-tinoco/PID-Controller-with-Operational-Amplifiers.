Design of a PID controller using different arrays of operational amplifiers in order to be able to regulate the temperature of a freezer.
For this application an LM35 sensor was used, because it is a sensor that does not require to be connected to a microprocessor to perform the temperature measurement and delivers an analogue output signal.

In addition, LM741 operational amplifiers were used, these general purpose operational amplifiers have a high performance in temperatures from -55° C to 125° C, another reason why this model was used was the fact that it has a protection against overloads at the input and output of each power supply pin.

Finally, a power stage was used to amplify the current in order to supply an actuator capable of temperature correction. However, the actuator was not included because the main focus is on the development of the controller.
In this power stage, BC337 (NPN) and BC327 (PNP) bipolar transistors were used, as they are a common model in small motor driver applications.

If you wish to consult the calculations, a PDF document with all the calculations will be attached.

To check the correct operation of the circuit, simulations were carried out in LTSpice. As the one shown below where I try to obtain a gain of 10 at a voltage of 0.5 Volts.

![image](https://github.com/ricardo-ugalde-tinoco/PID-Controller-with-Operational-Amplifiers./assets/154283114/49e2dd0b-9fc9-4ee1-8ecf-9068d9ef3933)
