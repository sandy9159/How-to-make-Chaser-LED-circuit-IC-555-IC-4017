![image](https://user-images.githubusercontent.com/19898602/127034323-828bca3f-f4a9-46fc-a44e-9728f5a2b58f.png)

An LED chaser or LED running light can be used as a decorative light, fancy light, chasing taillight for vehicles, etc.

The circuit consists of a 555 astable multivibrator circuit and a 4017 counter using IC. The output of the 555 generates a square wave 

or clock input for the decade counter. For each positive edge triggering of the clock input, 

the counter shifts the high state of the output in a sequence from output 0 to output 9.

In a 4017 counter IC, only one output will be high at a time and the remaining outputs will be in the low state. 

And the shifting cycle repeats like a ring counter. Thus the LEDs will visually seem like a rotating.

# COMPONENT USED

> IC 555 :- https://amzn.to/2PyeshF


> IC 4017 :- https://amzn.to/2o5NWQs


> LED :-  https://amzn.to/2wj3Meb


> 10K POT :- https://amzn.to/2MRiTWe


> 10uF CAP. :- https://amzn.to/2MRkdZc

> CUTOM PCB from [JLCPCB](https://jlcpcb.com/IAT )

![image](https://user-images.githubusercontent.com/19898602/127035696-3c2b934d-ea32-49e7-9335-e65749236efe.png)



# CIRCUIT DIAGRAM

![image](https://user-images.githubusercontent.com/19898602/127035558-8c419e30-cd8b-4157-b69d-1808963fccb6.png)


![image](https://user-images.githubusercontent.com/19898602/127035600-12c077a3-391a-40af-afea-05d5c318168e.png)

Here the Chaser circuit is designed with an ON time of 0.047s for each LED. 

The speed of the chaser can be varied by adjusting the time period of the clock input. 

That is the time period of the 555 astable multivibrator circuit, which can be calculated as T = .69 (R1+2R2) C.

You can see that the 555 timer wired as an astable multivibrator and its output is connected to the clock input of 4017 counter IC. 

The output frequency of the 555 timer is determined by the resistors R1, RV1 and capacitor C1. VCC (8th pin) and GND (1st pin) is connected to the power supply. 

Reset (RST – 4th pin) is connected directly to the positive power supply to avoid accidental reset of 555 timer. 

Control Voltage (CV – 5th pin) is not used, so to avoid high frequency noises we are connecting a capacitor (C2 – 0.01μF) to the ground.

LED D1 is used to indicate the output of 555 IC and the resistor R3 is for current limiting.

Similarly VDD (16th pin) and VSS (8th pin) of the CD4017 IC is connected directly to the power supply. Clock enable (13th pin) is an active low input, 

so it is connected to ground. Clock input (14th pin) is connected to the output of 555 timer. Each decoded output pins (Q0 ~ Q9) is connected to LED. 

Resistor R3 is used for current limiting. Only one resistor is required for limiting current through all LEDs since only one LED will turn on at a time.



# ORDERING PCB

![image](https://user-images.githubusercontent.com/19898602/127035804-9f17bfbc-5856-45ab-aee1-fad60aa37b29.png)


![image](https://user-images.githubusercontent.com/19898602/127035846-49fce94d-508b-41bc-a984-35e2139bfaf7.png)

![image](https://user-images.githubusercontent.com/19898602/127036369-e8374ebd-599a-456b-81b3-5e39aa5987e9.png)


First of all I design the PCB in Easy EDA PCB designing platform 
I have order PCB from ![image](https://user-images.githubusercontent.com/19898602/127036400-a2b4b22f-4b1c-42c4-823b-22eac63dc52f.png)
because ![image](https://user-images.githubusercontent.com/19898602/127036423-dfe9720a-00a5-4fa1-a10f-281f479d19f1.png) have very affordable rates for PCB 

like only 2$ for 1 - 4 layer PCB, you will get high quality PCB FROM ![image](https://user-images.githubusercontent.com/19898602/127036627-5726097b-a81d-4128-b1bb-186724a94120.png)
 in very short time you can surly can consider ![image](https://user-images.githubusercontent.com/19898602/127036677-db75a7f0-b7b6-40d5-890a-79db6516f316.png) or your future
 
 PCB needs.



