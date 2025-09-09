# Multi-SER-pe

[cite_start]This repository contains the official code and resources for the paper: **"Emotion Recognition in Multi-speaker Scenarios for Social Robots"**[cite: 1].

## About The Project

[cite_start]Social robots need to understand human emotions to interact naturally and effectively[cite: 27, 548, 551]. [cite_start]However, their ability to do so is often limited in real-world environments where background noise and multiple people speaking at once can interfere with emotion detection systems[cite: 13, 29].

[cite_start]This project addresses that challenge by introducing a complete pipeline that first separates individual voices from a noisy, multi-speaker audio stream and then identifies the emotion in each separated voice[cite: 14, 30, 183].

Key contributions of our work include:
* [cite_start]**A Novel Framework:** We propose a two-stage system that integrates a Blind Source Separation (BSS) model to isolate voices, followed by a Speech Emotion Recognition (SER) model to classify emotions[cite: 183].
* [cite_start]**Enhanced Accuracy:** Our fine-tuned models achieve a significant improvement in emotion recognition, reaching **84.62%** accuracy in clean conditions, **76.78%** in noisy environments, and **63.19%** in highly challenging (noisy and reverberant) scenarios[cite: 486, 489].
* [cite_start]**Database Adaptation:** We developed a methodology to adapt and merge existing emotional speech databases (RAVDESS, TESS, SAVEE, CREMA-D) to create realistic and challenging audio mixtures for training and testing[cite: 34, 207, 218].
* [cite_start]**Multilingual Validation:** The system's robustness was validated by fine-tuning and testing it on a new Spanish-language dataset recorded in Peru, demonstrating its adaptability to different languages and real-world conditions[cite: 433, 491, 518].

[cite_start]The code and resources provided here allow for the replication of our experiments and serve as a foundation for future research in robust human-robot interaction[cite: 449].

**Link to resources:** [https://drive.google.com/drive/folders/114nXHm5l5vQjDKp_OhFTlY6m62NuulTn?usp=sharing](https://drive.google.com/drive/folders/114nXHm5l5vQjDKp_OhFTlY6m62NuulTn?usp=sharing)
