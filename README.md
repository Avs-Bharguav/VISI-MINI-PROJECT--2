# VISI-MINI-PROJECT--2
Noise, Delay and Power Analysis of CMOS inverter build using skywater130nm pdk  
## Softwares  
*esim* - Schematic drawing and netlist generation.  
*Nspice* - For graphical analysis, delay calculations, power analysis, dc and transieant analysis and noise calculations.  

## DC Analysis  
You can go to the DCanalysis folder and check the screenshorts for the esim schematic settings.  
Here following is the schematic and the output viewed using ngspice. In the folder you can also find the ngspice codes used like for ploting 
plot vout vin.  

  
![dcanalysis Schematic](https://github.com/Avs-Bharguav/VISI-MINI-PROJECT--2/blob/main/DCanalysis/Screenshot%20from%202023-06-29%2019-03-49.png)  
![dc analysis output]()  
Here the Vm(where the output voltage and the input voltage are same) was found to be 0.67879v. 
And the noise margin was found to be Vil= , Vih = , Voi = , V0h = ,.  
Note: As we increase the size of the pmos the Vm come close to 0.5v. The Vm is not exactly in the middle as that is achived when we use a ratio of 3 or more between Wp and Wn.  





