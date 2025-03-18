## Overview
This repository contains my implementation of a transformer-based model for speaker classification. The project leverages the power of self-attention—drawing inspiration from the seminal paper "Attention is All You Need"—to process sequences of audio features and accurately predict the speaker among 600 candidates.

The main objective of this project is to perform multi-class classification on speech data. Each audio sample is represented as a sequence of pre-processed features, and the model uses self-attention mechanisms to capture both local and global dependencies within these sequences. The dataset consists of:

- Training Set: 62,464 audio samples with speaker labels
- Test Set: 6,944 audio samples

## Outcomes
- This project demonstrates a solid understanding of transformer architectures and self-attention mechanisms.
- It provides hands-on experience with processing sequential audio data and tackling the challenges of speaker recognition.
- The assignment required building a model from scratch (without using pre-trained networks), which allowed me to explore various configurations and even experiment with transformer variants such as conformers.
- The end-to-end implementation—from data loading and model design to training and evaluation—mirrors real-world challenges in speech classification tasks.
