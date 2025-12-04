# EEG_Classification
Auditory and Visual Rhythm Omission EEG Classification using Hybrid TLBO and Differential Evolution based Channel Selection

**Note**
This exploratory work was conducted between September 2022 to April 2023

**Introduction**
Electroencephalography (EEG) is widely used for neurological diagnosis and cognitive state analysis. Manual interpretation is time-consuming, expertise-dependent, and error-prone.

**Contents**
This repository explores automatic EEG signal classification using:
Hybrid Teaching-Learning-Based Optimization (TLBO) + Differential Evolution (DE) for optimal channel selection - This notebook implements a hybrid meta-heuristic optimization strategy for EEG channel selection. It introduces a modified binary TLBO process enhanced by Differential Evolution mutation

Temporal Convolutional Networks (TCN) and ResNet-based deep models for sequence learning
Benchmark evaluation on Auditory & Visual Rhythm Omission EEG dataset - Focuses on sequence modeling of EEG time-series using Temporal Convolutional Networks (TCNs)

Residual Deep Network for EEG - Implements a 1D-CNN residual architecture adapted from deep vision networks

The final objective was to increase classification accuracy while reducing the number of channels required for reliable prediction.

