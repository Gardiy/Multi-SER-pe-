# Multi-SER-pe

This repository contains the official code and resources for the paper: **"Emotion Recognition in Multi-speaker Scenarios for Social Robots"**.

## About The Project

Social robots need to understand human emotions to interact naturally and effectively. However, their ability to do so is often limited in real-world environments where background noise and multiple people speaking at once can interfere with emotion detection systems.

This project addresses that challenge by introducing a complete pipeline that first separates individual voices from a noisy, multi-speaker audio stream and then identifies the emotion in each separated voice.

Key contributions of our work include:
* **A Novel Framework:** We propose a two-stage system that integrates a Blind Source Separation (BSS) model to isolate voices, followed by a Speech Emotion Recognition (SER) model to classify emotions.
* **Enhanced Accuracy:** Our fine-tuned models achieve a significant improvement in emotion recognition, reaching **84.62%** accuracy in clean conditions, **76.78%** in noisy environments, and **63.19%** in highly challenging (noisy and reverberant) scenarios.
* **Database Adaptation:** We developed a methodology to adapt and merge existing emotional speech databases (RAVDESS, TESS, SAVEE, CREMA-D) to create realistic and challenging audio mixtures for training and testing.
* **Multilingual Validation:** The system's robustness was validated by fine-tuning and testing it on a new Spanish-language dataset recorded in Peru, demonstrating its adaptability to different languages and real-world conditions.

The fine-tuning process was carried out using the [SpeechBrain](https://arxiv.org/abs/2106.04624) toolkit, applying its default hyperparameters. This optimization methodology is supported by the work of [Subakan et al.](https://ieeexplore.ieee.org/document/9902821) on model adaptability.

The code and resources provided here allow for the replication of our experiments and serve as a foundation for future research in robust human-robot interaction.

**Link to resources:** [https://drive.google.com/drive/folders/114nXHm5l5vQjDKp_OhFTlY6m62NuulTn?usp=sharing](https://drive.google.com/drive/folders/114nXHm5l5vQjDKp_OhFTlY6m62NuulTn?usp=sharing)
