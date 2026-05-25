# ASD (Autism Spectrum Disorder) Emotion-Adaptive Music Generation

This project explores emotion-responsive music generation using EEG and EDA physiological signals. It uses the DEAP dataset for emotion prediction and tests how simulated ASD physiological patterns may affect predicted emotions and adaptive music features.

## Overview

The goal of this project is to build a computational pipeline that connects physiological signals, emotion recognition, and music feature mapping. The notebook predicts emotional states from EEG and EDA data, then maps those predictions to music-related features such as tempo, density, mode, and harmony. The project includes literature-based simulated ASD physiological conditions to examine how differences in signal patterns may influence emotion prediction and music feature selection. Music-based interventions have shown promise for individuals with ASD because music can support emotional expression, self-regulation, and structured engagement. We explore the potential of generative music systems to create more adaptive, emotion-responsive interventions.

## Features (as of 5/24/26)

- EEG and EDA data processing
- Emotion prediction using deep learning models
- DEAP dataset-based training workflow
- Participant-level train/validation/test splitting
- GRU and MLP model training
- MC-dropout uncertainty estimation
- ASD-simulated physiological pattern comparison
- Emotion-to-music feature mapping
- Saved checkpoints, results, and summary outputs

## Technologies Used

- Python
- Google Colab / Jupyter Notebook
- PyTorch
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## Project File

- `ASD_AI_Music_Generation_Colab_hybrid_architecture.ipynb`  
  Main notebook containing data processing, model training, evaluation, ASD simulation testing, and music feature mapping.
