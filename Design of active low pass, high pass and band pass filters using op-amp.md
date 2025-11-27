# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DESIGN OF ACTIVE LOW PASS,HIGH PASS AND BAND PASS FILTERS USING OP-AMP 

## AIM: 

To design and obtain the frequency response of 
i) First order Low Pass Filter (LPF) 
ii) First order High Pass Filter (HPF) 
iii) Band pass filter
 
## APPARATUS REQUIRED

<img width="625" height="170" alt="image" src="https://github.com/user-attachments/assets/900fc8b3-3a8c-4208-bf52-98cc9e281e21" />

## THEORY
## LOW PASS FILTER 
 A LPF allows frequencies from 0 to higher cut of frequency, fH.  At fH the gain is 0.707 
Amax, and after fH gain decreases at a constant rate with an increase in frequency.  The gain 
decreases 20dB each time the frequency is increased by 10.  Hence the rate at which the gain 
rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in 
frequency.  The frequency f=fH is called the cut off frequency because the gain of the filter at this 
frequency is down by 3 dB from 0 Hz.  Other equivalent terms for cut-off frequency are -3dB 
frequency, break frequency, or corner frequency.
# HIGH PASS FILTER 
The frequency at which the magnitude of the gain is 0.707 times the maximum value of 
gain is called low cut off frequency.  Obviously, all frequencies higher than fL are pass band 
frequencies with the highest frequency determined by the closed –loop band width all of the op
amp. 
# BAND PASS FILTER 
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > 
fL.  Any input frequency outside this pass band is attenuated.  There are two types of band-pass 
filters.  Wide band pass and Narrow band pass filters.  We can define a filter as wide band pass if 
its quality factor Q <10.  If Q>10, then we call the filter a narrow band pass filter.  A wide band 
pass filter can be formed by simply cascading high-pass and low-pass sections.  The order of 
band pass filter depends on the order of high pass and low pass sections.

## CIRCUIT DIAGRAM: 
## LOW_PASS
<img width="641" height="332" alt="image" src="https://github.com/user-attachments/assets/b049b725-90ab-4cc2-9b36-4bbd1ce18b0e" />

## HIGH-PASS
<img width="625" height="354" alt="image" src="https://github.com/user-attachments/assets/076103df-17a3-4bb6-b1d9-2b1a9ae0650e" />

## BAND-PASS
<img width="687" height="390" alt="image" src="https://github.com/user-attachments/assets/93506be7-98fe-457d-9b03-4cf9e934b437" />

## MODEL GRAPH:
## LOW_PASS
<img width="647" height="462" alt="image" src="https://github.com/user-attachments/assets/b0698ef3-2d40-4ae5-9f36-4ec024934009" />

## HIGH-PASS
<img width="582" height="418" alt="image" src="https://github.com/user-attachments/assets/4b765636-5ae5-4f89-8968-73f333f1754d" />

## BAND-PASS
<img width="643" height="456" alt="image" src="https://github.com/user-attachments/assets/f7342668-9bb2-44bf-90fc-9d6cb04edbd7" />

## PROCEDURE - (LPF & HPF): 
1. Connect the circuit as shown in the circuit diagram. 
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. 
select the value of R1 & Rf depending on desired passband gain Af.. 
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
4. Tabulate the output voltage Vo with respect to different values of input frequency. 
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to  get approximately the same characteristic as shown in the model graph. 
# PROCEDURE:BAND PASS FILTER 
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given 
frequencies. 
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF 
followed by a LPF (i.e) HPF in series with LPF. 
3. Connect the circuit as shown in the circuit diagram. 
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
5. Tabulate the output voltage Vo with respect to different values of input frequency. 
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to get approximately the same characteristic as shown in the model graph

## DESIGN:LPF & HPF:

<img width="429" height="324" alt="image" src="https://github.com/user-attachments/assets/b0f0ac0a-3006-494c-9096-e91ae2d6e87c" />

# DESIGN: BAND PASS FILTER
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.  
1. Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency 
of HPF as fL = 1 KHz.  
2. Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf.  
Let C = 0.1μf.  
3. Calculate R from the expression.  
Given: fH = 2KHz  = 1/ (2πR1C1) 
   Let C1 = 0.1 µF, R1 = 7.9 KΩ 
Given: fL = 400Hz  = 1/ (2πR2C2) 
   Let C2 = 0.1 µF, R2 = 39.8 KΩ 
  Pass band Gain=4 
   Now   Ao = 1 + (Rf / R1)  
               2-1=(Rf / Ri) 
                Ri = Rf 
                 Let  Ri = Rf = 10 KΩ
## TABULATION:
## LOW_PASS
![WhatsApp Image 2025-11-27 at 18 03 11_f80b5c8c](https://github.com/user-attachments/assets/4caf0ef8-371f-48fa-9993-9e90a7ad6624)

## HIGH-PASS
![WhatsApp Image 2025-11-27 at 18 02 52_e8f75cd0](https://github.com/user-attachments/assets/abf8d646-50d1-4cd9-99ed-f277bc12199d)

## BAND-PASS
![WhatsApp Image 2025-11-27 at 18 02 31_72f25857](https://github.com/user-attachments/assets/8a722172-2e75-4be5-bfa2-47326d6f6841)

## GRAPH:
## LOW_PASS
![WhatsApp Image 2025-11-27 at 18 05 52_73871517](https://github.com/user-attachments/assets/d0117919-694a-41d4-8ce7-656d4f33e953)

## HIGH-PASS
![WhatsApp Image 2025-11-27 at 18 05 52_2f729815](https://github.com/user-attachments/assets/190beef9-bb13-4933-aa61-d6e5336a1a6b)

## BAND-PASS
![WhatsApp Image 2025-11-27 at 18 05 52_c2e95eba](https://github.com/user-attachments/assets/f72d6857-231c-402f-a9dc-a828d6811d9a)

 ## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 

