## Description
This project targets at identification and control of heater-sensor coupled system hosted on Arduino Leo. Multiple methods have been utilized
to identify the given system. This gray box modelling process included FODPT, SODPT and Physical Non-linear model. A brief discussion 
of the procedure used could be found in the file 'identification.pdf'. The model which generalized best is later utilized to create a Model Predictive Controller with general step disturbance rejection. This model could be found in the zip folder named *Tracking.zip*, within which, the file *heater_mpc.m* could be utilized to access the algorithm.
