# 64-QAM-OFDM-transmission-chain
Introduction:

1)The OFDM system is one of the most widely used modern techniques in mobile radio communication networks for efficiently transmitting various forms of digital data compared to other existing traditional techniques.
Representation of the OFDM Transmission Chain:
Transmitter:

2)Convolutional Coding: The encoder consists of mm shift registers with KK binary elements. A combinatorial logic made up of XOR function linear generators generates the blocks of NN binary elements provided by the encoder.

64-QAM Modulation: This is a form of modulation with 64 states, each representing 6 bits by modifying amplitude and phase.

3)IFFT: The Inverse Fast Fourier Transform (IFFT) is an algorithm for computing the inverse of the discrete Fourier transform (DFT), transforming discrete data from the frequency domain to the time domain.

4)Cyclic Prefix: OFDM uses cyclic prefixes to combat multipath propagation by facilitating channel estimation. However, increasing the length of the cyclic prefix will increase the bandwidth of an OFDM symbol.
Receiver:

5)Cyclic Prefix Removal: This involves removing the extensions, in this case, a prefix of 28 for a block of 64.

6)FFT: The Fast Fourier Transform (FFT) allows the transformation of discrete data from the time domain to the frequency domain.

8)Demodulation: This extracts the original information-bearing signal from a carrier wave, converting analog to digital.

Information Decoding: The Viterbi algorithm is used to decode the information.

    Constraint Length: 7
    Rate: 1/2
    Generator Polynomials: A = 133(1011011); B = 171(1111001)
