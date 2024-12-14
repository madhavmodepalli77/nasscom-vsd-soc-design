**Digital VLSI SoC Design**
We will be designing an Application Specific Integrated Circuit (ASIC) from the Register Transfer Level (RTL) to the Graphical Data System (GDS) file using the OpenLane ASIC flow.

**DAY-1**
**OpenLane: Introduction to Components of Open-Source Digital ASIC Design**
Simplified RTl to GDS Flow
![image](https://github.com/user-attachments/assets/671a1de3-2675-46cf-ad5b-c80d89b3034e)
**OpenLANE Detailed ASIC Design Flow**
![image](https://github.com/user-attachments/assets/9073d21c-7dfd-4026-821d-c1f385a5a2fa)
**Labwork:** Flop ratio = number of DFF/Number of cells post synthesis

Invoke the openLANE_flow and flow.tcl with the below steps.

$ docker

bash-4.2$ ./flow.tcl -interactive

% package require openlane 0.9

% prep -design picorv32a

![image](https://github.com/user-attachments/assets/e741975a-baeb-411e-897e-da6fd23988f8)

![image](https://github.com/user-attachments/assets/76fe9c04-cd87-46c3-85ba-345b98ffbbf0)

A new runs directory is created with current date
![image](https://github.com/user-attachments/assets/66e12904-dbf2-4120-986d-7ad8cca48614)

Run the synthesis for the current design

% run_synthesis
![image](https://github.com/user-attachments/assets/df7ebdb9-524f-4c72-adbf-3d989a02c349)

![image](https://github.com/user-attachments/assets/ffb92cbd-96e3-4973-a1c6-da2d18d184ee)

![image](https://github.com/user-attachments/assets/5de8a963-f3b3-432b-a743-07ea64f4d495)

Number of D FF : 1613

Number of Cells : 14876

Flop ratio = 10.842%


