# Power Spectral Density (PSD) of a Music Signal

## Description
This MATLAB project captures audio, visualizes it in the time domain, and computes its Power Spectral Density (PSD) to examine the frequency distribution of the signal.

## Features
- Records a 10-second audio signal.
- Retains control until recording is done.
- Creates a numeric array to plot the audio samples.
- Computes and displays the PSD using Welch's method.

## Prerequisites
- MATLAB installed.
- A working microphone for audio input.

## How It Works
1. Initializes an audio recorder.
2. Captures a 10-second audio signal.
3. Retains control until the recording is complete.
4. Creates a numeric array for plotting the audio samples.
5. Plots the time-domain waveform.
6. Computes and visualizes the PSD by averaging the power spectrum estimates of all segments using the Welch Spectrum Estimate.
