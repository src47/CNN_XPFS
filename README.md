# CNN_XPFS
U-net convolutional neural network for the analysis of X-ray Photon Fluctuation Spectroscopy experiments. 

This repository contains the following folders: 

 - models

This folder contains the trained U-net model based on parameters from an accurate LCLS detector simulation. 

- data

This folder contains 1000 simulated frames corresponding to contrasts of 0.7 and 0.8. Here, the ground truth maps, the input detector images and the droplet images are stored. 

- example

Contains a notebook which shows how to run the CNN model and output the contrast and corresponding error bars. 
