# Reinforcement-Learning-for-optimizing-Concurrent-Fault-Detection-and-Classification
1. Objective:
Using Reinforcement Learning for optimizing Concurrent Fault Detection and Classification.

2.Models for Simultaneous/Concurrent Fault:
For Simultaneous/Concurrent Fault situations, deploy a Denoising Autoencoder (DAE) for feature extraction, followed by Gated Recurrent Unit (GRU) for feature learning.

3.Automatic Hyperparameter Tuning:
Both models incorporate automatic hyperparameter tuning.
Hyperparameter ranges and values:
CNN Layers: 0–5
LSTM Layers: 0–5
Dense Layers: 0–5
Epochs: 50–900
Max Pooling Layer: 0–1
Drop Layer: 0–2
Batch Normalization Layer: 0–2
Batch Size: 64–150
Learning Rate: 0.001–0.0001

4.Output:
Generate bar graphs for each identified fault.
The output will provide a clear visualization of the identified faults based on the implemented models.

Refrence research paper used for project : https://www.mdpi.com/1424-8220/22/11/4066
