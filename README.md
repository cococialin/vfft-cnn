# VFFT-CNN (Versatile Fast Fourier Transform Convolutional Neural Network)

A Tiny ML CNN that uses FFT Convolutions instead of traditional or normal convolutions.

This implementation shows that FFT Convolutions can process both small and large kernels with the same latency.

<img src="https://github.com/cococialin/vfft-cnn/FFT Convolution vs Normal Convolution.png" alt="FFT Convolution vs Normal Convolution" />

VFFT-CNN is design for the TinyML field to process large kernels with fewer convolutional layers, but it can also be suited for Deep CNNs by simply using it with more layers.

<img src="https://github.com/cococialin/vfft-cnn/VFFT-CNN Architecture.png" alt="VFFT-CNN Architecture" />

This CNN is based on the V-CNN (Versatile Convolutional Neural Network) that can be found here: <a href="https://ieeexplore.ieee.org/document/10310339"> https://ieeexplore.ieee.org/document/10310339 </a>

VFFT-CNN is first presented in my Phd Thesis titled: NATURAL INSPIRATION METHODS FOR ENHANCEMENT OF ENVIRONMENTAL INFORMATION RECOGNITION IN MOBILE COMPUTING PLATFORMS

If you find it usefull please cite it here or my PhD Thesis.
