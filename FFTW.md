## Fast Fourier Transformation:

Fast Fourier transforms are computed with the FFTW library.

A fast Fourier transform (FFT) algorithm computes the discrete Fourier transform (DFT) of a sequence, or its inverse (IFFT). Fourier analysis converts a signal from its original domain (often time or space) to a representation in the frequency domain and vice versa.

[see Wikipedia for more informations](https://en.wikipedia.org/wiki/Fast_Fourier_transform)

```
R = rand(5000,5000);tic(); Y = fft(R); toc
```


[Previous page](README.md)