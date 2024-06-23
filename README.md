# Drone localization using sound

**_Scripts where written using Python 3.11.0_**

- Folder [data](data) contains the data used for the project.
- Folder [outputs](outputs) contains the output files generated by the scripts.
- Folder [src](src) contains the scripts used for audio processing.

### Scripts

Most of the functions in the scripts require passing the path to the audio file as an argument.

- [bessel.py](src%2Fbessel.py) - filtering sound with Bessel filter. Main function - _bessel_filter()_
- [cutting.py](src%2Fcutting.py) - cutting audio files into smaller parts. Main function.
- [cwt.py](src%2Fcwt.py) - plots the continuous wavelet transform of the audio file.
- [derivatives.py](src%2Fderivatives.py) - calculates the derivatives and extremums of the signal.
- [dwt.py](src%2Fdwt.py) - plots the discrete wavelet transform of the audio file.
- [fft.py](src%2Ffft.py) - plots the fast fourier transform of the audio file.
- [iir.py](src%2Fiir.py) - filtering sound with Butterworth filter. Main function - _iir_filter()_
- [mel.py](src%2Fmel.py) - plots the mel spectrogram of the audio file.
- [phaseshift.py](src%2Fphaseshift.py) - calculates the phase shift of the signal.
- [rawaudio.py](src%2Frawaudio.py) - plots the raw audio signal.
- [stft.py](src%2Fstft.py) - plots the short-time fourier transform of the audio file.
- [tdoa.py](src%2Ftdoa.py) - calculates the time difference of arrival of the signal. Main function - _tdoa_mics()_
- [wavtocsv.py](src%2Fwavtocsv.py) - converts the audio file to a csv file.
