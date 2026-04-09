# DESIGN OF DIGITAL CHEBYSHEV LOW PASS FILTER USING BILINEAR TRANSFORMATION

# AIM:
To design a digital Chebyshev low pass filter using the bilinear transformation method in MATLAB satisfying the following constraints:

0.8≤∣H(ω)∣≤1.0;0≤ω≤0.2π

∣H(ω)∣≤0.2;0.32π≤ω≤π
Assume sampling period T=1second.

# APPARATUS REQUIRED :

MATLAB software
  
Computer system
  
Given Specifications

Passband edge frequency:

ω_p=0.2π

Stopband edge frequency:

ω_s=0.32π

Passband ripple:

A_p=-20〖log⁡〗_10 (0.8)≈1.94" dB"

Stopband attenuation:

A_s=-20〖log⁡〗_10 (0.2)≈13.98" dB"

Sampling period:

T=1" second"

# Theory:

Chebyshev filters provide a sharper transition between passband and stopband compared to Butterworth filters but allow ripples in the passband (Type-I).
The bilinear transformation converts an analog filter into a digital filter using:

s=2/T  (1-z^(-1))/(1+z^(-1) )

Frequency pre-warping is required to compensate for frequency warping introduced by bilinear transformation.
Steps involved:
Prewarp the digital frequencies.
Design an analog Chebyshev filter.
Convert it into a digital filter using bilinear transformation.
Plot magnitude and phase response.

# ALGORITHM :

1)Specify passband and stopband edge frequencies.

2)Convert digital frequencies into analog frequencies using pre-warping.

3)Calculate filter order using Chebyshev approximation.

4)Design analog Chebyshev low pass filter.

5)Convert analog filter to digital filter using bilinear transformation.

6)Plot frequency response using freqz.

7)Verify that the designed filter meets the given constraints.

# MATLAB CODE :
<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/3a91f6ab-5472-43f3-8548-9c9849a1b45c" />
<img width="1080" height="352" alt="image" src="https://github.com/user-attachments/assets/8bde3226-e640-4cf6-b092-76d1433e05a7" />

# OUTPUT GRAPH :
![WhatsApp Image 2026-04-08 at 12 21 53 PM](https://github.com/user-attachments/assets/836163d0-600c-4347-8933-5bea2b345623)


# RESULT:
A digital Chebyshev low pass filter satisfying the given specifications was successfully designed using the bilinear transformation method and its frequency response was verified using MATLAB.

