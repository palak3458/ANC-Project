# ANC-Project
Adaptive Noise Cancellation (ANC) Using LMS Algorithm

Designed and implemented an adaptive noise cancellation system in MATLAB to remove noise from audio signals using the Least Mean Squares (LMS) algorithm.
Generated reference noise signals, applied adaptive filtering, and analyzed the performance of the system.
Visualized and compared noisy and denoised audio signals using time-domain plots.
Gained hands-on experience with MATLAB’s audio processing tools (audioread, sound, dsp.LMSFilter) and adaptive filtering techniques.

The script performs the following tasks:

Loads an audio file you belong with me noisy.mp4.
Converts the audio from stereo to mono if necessary.
Defines and extracts a 1-second segment of noise from the beginning of the audio.
Repeats the noise segment to match the length of the audio signal.
Uses an LMS (Least Mean Square) filter to perform adaptive noise cancellation.
Plots the original and filtered audio signals for comparison.
