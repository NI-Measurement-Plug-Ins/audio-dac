# Frequency sweep measurement
This service performs Freyquency measurements: SNR, THD, THD+N, SFDR, Dynamic Range, Gain Error.

## Tested Hardware Setup 1

![alt text](meas-images/audio-dac-setup.PNG)


## InstrumentStudio Panel

### Usage

1. Select appropriate resource names, data line and channels according to the hardware setup and update other parameters as needed. Ensure the protocol settings are good. Please note that, measurement is working in I2S by default.
![alt text](meas-images/single-tone-measurement-launch.PNG)

2. Run the measurement. The frequency, amplitude, SNR, THD, THD+N, Dynamic Range, Gain error, SFDR values are calculated and displayed in the panel below.
![alt text](meas-images/freq-resp-ui.PNG)

3. The generated and acquired signals can be seen from time domain and frequency domain graphs.
![alt text](meas-images/frequency-sweep.PNG)
