# LabFab_DS2OS_Simulink
![LabFabSim_FullView](https://user-images.githubusercontent.com/88111965/221711108-1d28b9f1-a346-4fd3-9f25-301526560356.png)

Link to video of the Physical system being simulated (LabFab) ---> https://www.youtube.com/watch?v=5_MvuACnVRw

Most recent version labelled "LabFabSim2022a_10_6_2023.slx" contains all the attacks mentioned in the paper.

**To enable attacks, change attack probability within the sim (initially set to zero):**

**DOS example**

1.) Navigate to "HBW_Start (DOS)" subsystem  
2.) Select {...} (exit action) with "DOS attack location" label next to it  
3.) Change chanceDOS value to a range from 0.0 - 1.0  
4.) Run the simulation  
5.) Visualize results using ExportData2Excel.mlx script  
