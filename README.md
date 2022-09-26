# CNN_XPFS
U-net convolutional neural network for the analysis of X-ray Photon Fluctuation Spectroscopy experiments (XPFS). 

## Installation

To install requirements, `cd` into this repo directory and run:
```bash
$ pip install -r requirements/requirements.txt
```

## Usage

First make sure this repo directory is on the PYTHONPATH, e.g. by running:
```bash
docker pull slaclab/slac-ml:20211101.0
```

## Contents

This repository contains the following folders: 

 - models

This folder contains the trained U-net model based on parameters from an accurate LCLS detector simulation. Please refer to: https://www.nature.com/articles/s41598-021-98774-3 for more details on the implementation of the simulator.

- data

This folder contains 1000 simulated frames corresponding to contrasts of 0.7 and 0.8. Here, the ground truth maps, the input detector images and the droplet images are stored. 

- example

Contains a notebook which shows how to run the CNN model and output the contrast and corresponding error bars. 
