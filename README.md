# VISI-MINI-PROJECT--2
Noise, Delay and Power Analysis of CMOS inverter build using skywater130nm pdk  
## Softwares  
*esim* - Schematic drawing and netlist generation.  
*Nspice* - For graphical analysis, delay calculations, power analysis, dc and transieant analysis and noise calculations.  

## DC_Analysis  
You can go to the DCanalysis folder and check the screenshorts for the esim schematic settings and outputs.  
Here following is the schematic and the output viewed using ngspice. In the folder you can also find the ngspice codes used like for ploting 
plot vout vin.  

  
![dcanalysis Schematic](https://github.com/Avs-Bharguav/VISI-MINI-PROJECT--2/blob/main/DCanalysis/Screenshot%20from%202023-06-29%2019-03-49.png)  
![Dc output](https://github.com/Avs-Bharguav/VISI-MINI-PROJECT--2/assets/130825917/6fde03d7-cd8c-4902-9ec3-4049481fe19c)

Here the Vm(where the output voltage and the input voltage are same) was found to be 0.67879v. 
And the noise margin was found to be Vil= , Vih = , Voi = , V0h = ,.  
Note: As we increase the size of the pmos the Vm come close to 0.5v. The Vm is not exactly in the middle as that is achived when we use a ratio of 3 or more between Wp and Wn.  
## Delay_Analysis  
Next we do transieant analysis and calculate the propagation delays, rise time and fall time.   
You can now go to the delayanalysis folder and check out the schematic and esim settings for the transieant analysis.  
Here i am showing the schematic and output.    
![Schematic](https://github.com/Avs-Bharguav/VISI-MINI-PROJECT--2/assets/130825917/a0df5ef0-c7b9-4d60-b54f-9a03949027d8)    


![output](https://github.com/Avs-Bharguav/VISI-MINI-PROJECT--2/assets/130825917/eac0ce20-917b-4910-b7e1-937a7a17efd1)  



![output](https://github.com/Avs-Bharguav/VISI-MINI-PROJECT--2/assets/130825917/962936e8-44ed-4742-869f-fc61e4cd96df)   


After that you can go to the ngspice window and calculate the propagation delay that is time delay between Vin50 to vout50 that is 50% input voltage to 50% output voltage.  
You can fing all the ngspice code used to calculate in the screenshorts in the delayanalysis folder.  
we found: Vplh = 0.20767ns, Vphl = 3.22028ns, Trise = 0.101145ns and Tfall = 0.058780ns.  






