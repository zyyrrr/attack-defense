# attack-defense
Realization of paper: "Black Box Attack and NIDS Using Machine Learning for Malicious Traffic"

## Introduction
In order to detect the robustness of existing anomaly detection algorithms based on ML, we design and implement a black box attack method to evade network intrusion detection.  The method includes two parts:  
First, we use the features of Generative Adversarial Network (GAN) to generate adversarial samples to generate data packets that can evade anomaly detection.  
Then, we insert the forged data packets into the original malicious traffic so that the anomaly detectors cannot detect the malicious traffic.  
We find that the feature extraction of the existing anomaly detection algorithm has a loophole, so we propose a new defense model to make up for this loophole.  

## Dependencies
 ```pytorch 1```
 ```Python 3```
 
## Datasets
Four data sets, Kitsune, CICIDS2017, MAWILAB and UNSW-NB15, are used in this paper to evaluate the performance of our scheme.

## Demo Code
A demo script for "Performance Test of GAN" is provided in test(Mirai).ipynb.  
A demo script for "Evasion Performance Test of Insertion Attacks" is provided intest(Mirai) - insert to expand time.ipynb.  
A demo script for "Comparison of Two Feature Extraction Algorithms" is provided in ML classifiers(KitNET)_mirai_LinearAttenuation.ipynb.  
Three demo scripts for "FPDefense Detection Performance Test Before FPAttack" are provided in FPDefense(mirai)_detection.ipynb, FPDefense(mirai)_GRU_detection.ipynb and FPDefense_IntegratedLearning_detection.ipynb.  
Three demo scripts for "FPDefense Defense Performance Test After FPAttack" are provided in FPDefense(mirai)_defense.ipynb, FPDefense(mirai)_GRU_defense.ipynb and FPDefense_IntegratedLearning_defense.ipynb.  
