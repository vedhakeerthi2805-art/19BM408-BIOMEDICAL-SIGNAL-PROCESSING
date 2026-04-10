# DIF–FAST FOURIER TRANSFORM (FFT) USING RADIX-2 ALGORITHM
 
# Aim :
To compute the Fast Fourier Transform (FFT) of a discrete-time signal using the Radix-2 Decimation-in-Frequency (DIF) algorithm using MATLAB.
  
# Apparatus / Software Required :
Computer / Laptop

MATLAB software

# Theory :
The Fast Fourier Transform (FFT) is an efficient algorithm used to compute the Discrete Fourier Transform (DFT).
In the Radix-2 Decimation-in-Frequency (DIF) FFT:
	The frequency components are split first
	The input signal is combined initially
	Decimation happens in the frequency domain
	Butterfly operations start with larger blocks and proceed to smaller blocks
The Radix-2 DIF FFT requires the signal length to be a power of 2:

N=2^m

Key Difference from DIT:

DIT → decimation in time, bit-reversed input
  
DIF → decimation in frequency, bit-reversed output

 Key Features of DIF-FFT:
 
Decimation is done in frequency domain

Input is in natural order

Output is in bit-reversed order

FFT computation is done in log₂N stages

Twiddle factors are applied after subtraction

#  Algorithm :
1)Start the program

2)Define a discrete-time signal with length N=2^m

3)Perform FFT using Radix-2 DIF method

4)Compute the magnitude spectrum

5)Plot the FFT output

6)Stop the program

# MATLAB CODE :
<img width="658" height="1600" alt="image" src="https://github.com/user-attachments/assets/60af7707-d298-4d09-8f56-29927271e686" />

# OUTPUT GRAPH :
![WhatsApp Image 2026-04-10 at 6 47 28 PM](https://github.com/user-attachments/assets/d9aa9199-de5c-44a3-9bb4-eaf7e8a98294)



# RESULT :
Thus, the Fast Fourier Transform of the given discrete-time signal was successfully computed using the Radix-2 Decimation-in-Frequency (DIF) FFT algorithm in MATLAB.

