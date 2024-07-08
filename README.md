# Two-phase-pressure-drop-ANN-model

This project was done as a side piece of my thesis project to replace a 45 KL liquid oxygen tank.

This ANN model is used to predict the pressure drop of a saturated liquid, undergoing boiling into a two-phase, liquid-vapour mixture. 

This work was inspired by previous literature, where researchers constructed an ANN model to predict pressure drop for different two-phase flow patterns. 

**Data**

All data that I have used was taken from this GitHub repository: https://github.com/alejomonbar/CoINN

by downloading the data, and changing the name to 'trainData' - you should be able to run the code 

the data used has five inputs: quality, roughness, mass flux, and reynolds number (R)

these inputs are used to calculate frictional pressure drop 

the data is summarised in the below image: 
![image](https://github.com/tmow1/Two-phase-pressure-drop-ANN-model/assets/159899558/a1fa4f85-87c5-4918-8a95-1e7f195a7492)

**Results**

The ANN model has a mean absolute relative deviation (MARD) of 25%. 

This is relatively successful, as traditional two-phase model MARDs were around 29.9% - this ANN model is more accurate. 

The below image depicts predicted vs real results:
![image](https://github.com/tmow1/Two-phase-pressure-drop-ANN-model/assets/159899558/4bd9386b-cdfc-4810-a702-18064bc87f9b)

the significance, is that the ANN model tends to slightly underpredict pressure drop. 






