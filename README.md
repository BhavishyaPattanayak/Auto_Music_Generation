# Auto_Music_Generation

This repository contains an auto music generation model implemented using Long Short-Term Memory (LSTM) networks, a Convolutional Neural Network (CNN), and trained using the Adam optimizer. The model generates music in both sheet music format and playable audio format based on a provided dataset of MIDI files.

## Overview

- **Model Architecture**: The model architecture combines LSTM layers for sequence generation and a CNN for feature extraction from MIDI data.
- **Training**: The model is trained using the provided dataset for 50 epochs.
- **Outputs**: The model generates music in two formats:
  - **Sheet Music**: Music notation in a printable format.
  - **Playable Audio**: Audio files (e.g., MIDI or WAV) that can be played back.

## Dataset

The dataset for this project contains a collection of MIDI files. MIDI files provide a structured representation of music that includes notes, durations, and other musical elements. These files serve as the training data for the model.
