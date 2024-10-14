# VFFT-CNN (Versatile Fast Fourier Transform Convolutional Neural Network)

A Tiny ML CNN that uses FFT Convolutions instead of traditional or normal convolutions.

This implementation shows that FFT Convolutions can process both small and large kernels with the same latency.

![FFT Convolution vs Normal Convolution](https://github.com/cococialin/vfft-cnn/blob/main/FFT%20Convolution%20vs%20Normal%20Convolution.png?raw=true)

VFFT-CNN is design for the TinyML field to process large kernels with fewer convolutional layers, but it can also be suited for Deep CNNs by simply using it with more layers.

![VFFT-CNN Architecture](https://github.com/cococialin/vfft-cnn/blob/main/VFFT-CNN%20Architecture.jpg?raw-true)

To run the VFFT-CNN, first run the FFTConv2D code block, second run the VFFT-CNN code block, the you can use the model as the following example:

```
vfft_cnn = create_v_cnn_fft_model(shape, num_classes=n_class, flat=1, fil=[3,6,10], nl=[1,0,0], hid=[], csize = 32, padding="same")
```

This implementation is built on top of Keras and Tensorflow frameworks.

This CNN is based on the V-CNN (Versatile Convolutional Neural Network) that can be found here: <a href="https://ieeexplore.ieee.org/document/10310339"> https://ieeexplore.ieee.org/document/10310339 </a>

VFFT-CNN is first presented in my Phd Thesis titled: NATURAL INSPIRATION METHODS FOR ENHANCEMENT OF ENVIRONMENTAL INFORMATION RECOGNITION IN MOBILE COMPUTING PLATFORMS

If you find it usefull please cite it here or my PhD Thesis.
