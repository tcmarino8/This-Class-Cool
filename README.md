# Physics-188

Homework 4
Fisher Information Matrix, Independent Component Analysis

FIM: to design an experiment(uses hessian of log likelihood); can vary experiment design and predict level of expected error on given param.

Seems to be inverse of co-variance matrix



ICA: "rotate data" so each axis is as non gaussian as possible.

Use ICA to extract sound bits from an overlapped sound file. Using sklearn FastICA. 
Use X = AS + \mu where S is the vector containing the individual sounds, A is the mixing matric and \mu is the mean of X. All can be gathered from the ica model that you fit to the data. Data needs to be cenetered and whitened(mean to zero, normalize variance in all directions(treat source signals equally))

Can also conduct ICA for image analysis. Take overlapping images and with ICA you can separate them. Make sure data is 1D. Also done with PCA. Forgot to plot the images, I was silly back then
