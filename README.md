# STARRVision
This is a project using two LimeSDR radios to transmit live video from STARR's rockets to our ground station. The goal is to transmit four compressed video feeds during flight to achieve a full 360 degree view during flight. 

# Setup
## LimeSDR Config
To configure the LimeSDR for testing the gnuradio flowgraphs, the following command must be run:
```sh
limeConfig --rxen=1 --rxlo=2.445e9 --rxlpf=15e6 --txen=1 --txlo=2.445e9 --txlpf=16 --refclk=45e6 --samplerate=20e6 -ldebug
```
