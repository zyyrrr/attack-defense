# attack-defense
Realization of paper: "Black Box Attack and NIDS Using Machine Learning for Malicious Traffic"

## Introduction
In order to detect the robustness of existing anomaly detection algorithms based on ML, we design and implement a black box attack method to evade network intrusion detection.  The method includes two parts: 
****
First, we use the features of Generative Adversarial Network (GAN) to generate adversarial samples to generate data packets that can evade anomaly detection. 
Then, we insert the forged data packets into the original malicious traffic so that the anomaly detectors cannot detect the malicious traffic.
We find that the feature extraction of the existing anomaly detection algorithm has a loophole, so we propose a new defense model to make up for this loophole.

## Dependencies
 ```pytorch 1```
 ```Python 3```
 
## Datasets
Four data sets, Kitsune, CICIDS2017, MAWILAB and UNSW-NB15, are used in this paper to evaluate the performance of our scheme.

## Demo Code
