## EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
## SIMULATION OF SCHMITT TRIGGER

## AIM:
To Design and simulate the digital to analog converter (DAC) circuit using LT Spice

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1. Double click on LT Spice icon.

2. New schematic window open.

3. Pick and paste the required component from the library and draw the circuit diagram .

4. Complete the connection.

5. Select 1 voltage and select pulse width as 
Vinitial [V]: 5
       Von [V]: 0
       Tdelay [s]: 0
       Trise [s]: 1u
       Tfall [s]: 1u
               Ton [s]: 10m
        Tperiod [s]: 20m
        Ncycles: 100
Change the values of Ton = 20m , 40m, Tperiod  = 40m , 80m
For v2 and v3  keeping the other values constant.
6. Save the file by giving file name.

7. Click on the run option -->click advanced open -->select select transient analysis -->enter the amplitude time delay stop time value as (.tran 0 200 0 0.01).

8. Click on the run option -->simulation window opens-->place the probe -->output graph is obtained.

## CIRCUIT DIAGRAM:
### DAC:
<img width="1876" height="913" alt="519684755-ead98d02-9d2e-4609-b065-09d831235689" src="https://github.com/user-attachments/assets/d5282b04-2d14-4567-bfa6-af6cacf7d854" />


## OUTPUT GRAPH:
### DAC:
<img width="1919" height="619" alt="519685351-1d3e5699-76b3-434f-bbea-e0f3fba79171" src="https://github.com/user-attachments/assets/b04a1338-c893-48d1-a65b-51b8ae169460" />

![WhatsApp Image 2025-11-27 at 18 38 00_ef3ebdc6](https://github.com/user-attachments/assets/886b89c8-8452-4093-96d1-c5bee32e3d82)


## RESULT:
Thus the LT-SPICE tool has been studied and digital to analog converter (DAC) circuit is simulated.
