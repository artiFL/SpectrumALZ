# Spectrum Analizer 0-4400MHz
## Introduction
The spectrum analyzer is based on 2 high-frequency frequency generators adf 4351 and one low-frequency generator ss 5351, connected according to the cross-multiplexing scheme.
The signal mixing and filtering circuit is based on the IAM 81008 microwave multiplex and a low-pass filter with a cutoff frequency of 130 kHz, the signal is digitized on the ADC of the microcontroller
## Device
Initially, the device was conceived as a stationary analyzer with an external 12V power supply, a display and a control keypad, but due to many ambiguous moments, it was decided to release the initial prototype without external control, but with the ability to connect the touch screen with an external controller via i2c
## Future
- Frequency spectrum display 0 - 4300 MHz
- Frequency generation at SMA 0 - 4300 MHz
- Connecting to the Desktop application via Wi-Fi, usb
- Vector circuit analysis
## Display 
The simplest 7-inch display with RGB interface support was chosen as the display.
![alt text](https://github.com/artiFL/SpectrumALZ/blob/master/Image/Disp.jpg?raw=true)
## PCB
![alt text](https://github.com/artiFL/SpectrumALZ/blob/master/Image/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-01-22%20144712.png?raw=true)
![alt text](https://github.com/artiFL/SpectrumALZ/blob/master/Image/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-01-22%20144736.png?raw=true)
