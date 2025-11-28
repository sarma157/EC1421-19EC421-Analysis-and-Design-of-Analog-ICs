## EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
## DIGITAL TO ANALOG CONVERTER

## AIM:
To Design and simulate the digital to analog converter (DAC) circuit using LT Spice

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1. Double click on LT Spice icon.
2. 
3. New schematic window open.

4. Pick and paste the required component from the library and draw the circuit diagram .

5. Complete the connection.

6. Select 1 voltage and select pulse width as 
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
7. Save the file by giving file name.

8. Click on the run option -->click advanced open -->select select transient analysis -->enter the amplitude time delay stop time value as (.tran 0 200 0 0.01).

9. Click on the run option -->simulation window opens-->place the probe -->output graph is obtained.

## CIRCUIT DIAGRAM:
### DAC:
![WhatsApp Image 2025-11-28 at 09 09 55_bd5ca038](https://github.com/user-attachments/assets/e8bae9cf-613d-42ec-8dda-998c71b8fb83)


## OUTPUT GRAPH:
### DAC:
![WhatsApp Image 2025-11-28 at 09 10 04_c9dddac1](https://github.com/user-attachments/assets/b8a55d45-7212-4256-9066-73ca1f059c8b)


## RESULT:
Thus the LT-SPICE tool has been studied and digital to analog converter (DAC) circuit is simulated.
