# VISI-MINI-PROJECT--2
Noise, Delay and Power Analysis of CMOS inverter build using skywater130nm pdk  
*NOTE: FACING SOME PROBLEMS IN DISPLAYING IMAGES IN PUBLIC DOMAIN. YOU CAN GO TO RESPECTIVE FOLDER AND VIEW THE SCREENSHORTS.*  
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
## Power_Analysis  
The following schematic is drawn for the power analysis. A extra load capacitor is added.  



![Schematic](https://github.com/Avs-Bharguav/VISI-MINI-PROJECT--2/assets/130825917/fd833ce7-18cd-490a-964e-4ebfc7c2336a)  
Again you can go to the poweranalysis folder to check the settings used.  
The next graph shows the current flow through the inverter. For the power calculation we integrate the over all current flown per cycle and multiply with the voltage that is 1.8v.  

![current](https://github.com/Avs-Bharguav/VISI-MINI-PROJECT--2/assets/130825917/3f42e269-b1bd-4db9-9b4c-f34db1b585ae)  
The calculations and the codes used for the power calculations can be fount in the screenshort in the folder.  
We have calculater power for two cases 1> nmos w=2 l=1 2> nmos w=1 l=0.5.  
case 1 Power = 1.68462uW; case 2 power = 0.578992uW.  

