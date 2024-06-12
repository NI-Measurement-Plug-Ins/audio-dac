# Audio DAC - LabVIEW

## Overview

This MeasurementLink LabVIEW plugin makes measurements for Audio DACs.

The tests generate the digital signal and measures the audio analog output of the DAC

![alt text](docs/images/Single%20tone%20measurement.JPG)


## Key Features

 - Generates analog signal supporting below protocols
   - I2S
   - Left Justified
   - Right Justified
   - TDM
 
 - Single tone measurements (for single channel and dual channel)
   - THD
   - THD+N
   - SNR
   - SFDR
   - Dynamic range
   - Gain error 
 - Stepped Frequency Sweep
 - Crosstalk
   

## Software Installation
(*This section is applicable if you only want to use the pre-compiled plug-ins. If you want to open the source code, go to [software development](docs/software-development.md).*)  
Install from NI Package Manager:

- NI-DCPower (As recommended by InstrumentStudio, if SMUs are used for powering up the DUT)
- InstrumentStudio (2024 Q1 or higher)
- Measurement Link (2024 Q1 or higher)
- NI-DAQmx (2022 Q3 or higher)
- NI-Digital Audio Acquisition and Generation Toolkit (2023 Q3 or higher)

Download the latest NI package from the releases section of this repo or add the feed to NI Package Manager to get updates from this repo and other in this community. To use the NI Package Manager feeds, refer to this: [Subscribing to package feeds](https://github.com/NI-MeasurementLink-Plug-Ins/package-manager-feeds)

## Getting Started
When you are ready to start using the software, check out [this](docs/help.md).

## Contributing
Use the instructions in [software development](docs/software-development.md) for setting up a development environment and overview of the code.
