# Spectrum Analizer 0-4400MHz
## Introduction
The spectrum analyzer is based on 2 high-frequency frequency generators adf 4351 and one low-frequency generator ss 5351, connected according to the cross-multiplexing scheme.
The signal mixing and filtering circuit is based on the IAM 81008 microwave multiplex and a low-pass filter with a cutoff frequency of 130 kHz, the signal is digitized on the ADC of the microcontroller
## Device
Initially, the device was conceived as a stationary analyzer with an external 12V power supply, a display and a control keypad, but due to many ambiguous moments, it was decided to release the initial prototype without external control, but with the ability to connect the touch screen with an external controller via i2c
## Display 
The simplest 7-inch display with RGB interface support was chosen as the display.
![alt text]([http://url/to/img.png](https://github.com/artiFL/SpectrumALZ/blob/master/Image/Disp.jpg))

