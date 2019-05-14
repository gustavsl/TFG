# TFG
This is my undergraduate thesis about a microcontroller-based automatic baby cry detection system.

It's based on a NXP Kinetis KL25 microcontroller running a neural network inference.

The neural network is fed MFCC (Mel-frequency cepstrum coefficients) extracted from audio data captured from the board's microphone and trained against baby cry samples to detect silence vs baby cries.
