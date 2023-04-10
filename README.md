# Cryogenic Distillation for N2 Rejection
 The simulation is about Nitrogen Rejection using Cryogenic Distillation in Aspen HYSYS

Cryogenic condition refer to a process that occur under 0 degree celciuse which is the freezing temperature of a water. Nitrogen gas does make the Natural Gas(NG) sweet or sour but problem of nitrogen gas for being in the NG is it lower the heating value. 

Softwere use for this simulation :
![Aspen Version](https://img.shields.io/badge/Aspen_Hysys-v12.1-Green)

The Process Flow Diagram from the process

![image](https://user-images.githubusercontent.com/121662875/230880899-55a81fff-3130-4a46-be63-0d5104568619.png)
The temperature decreases as we move from left to right indicated by the Line colour

# Summary of view
The colour for every line is set to change by the change of temperature. By using the Editor in the Flowsheet/Modify tab, different variable can be chose to indicate the changes in the process line. For this simulation we use the temperature as the variable and set 0 degree celcius as one of the boudry to see which line has reached the cryogenic temperature. The LNG working mechanism is same as the Shell and tube heat exchanger but the number of the cold / hot fluid is not fixed to one stream. The relevence of having the LNG is to optimize the Heat intergration between heating fluid and cooling fluid. The NG pipelines is commonly hot that will require some cooling and the N2 gas pipeline is naturally cold that can be use as cooling fluid. 

# The impact
From the simulation, more than half of the pipeline will require a different type of material of construction(MOC) and special insulation for the heat loss to be at minumum. 

# Made by :
1. Abdul_Hafiz
2. Surayya
