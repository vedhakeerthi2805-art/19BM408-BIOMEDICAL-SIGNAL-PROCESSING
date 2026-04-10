# DIT–FAST FOURIER TRANSFORM (FFT) USING RADIX-2 ALGORITHM
# AIM:
To compute the Fast Fourier Transform (FFT) of a discrete-time signal using the Radix-2 Decimation-in-Time (DIT) algorithm using MATLAB.

# APPARATUS REQUIRED :
•	Computer / Laptop

•	MATLAB software

# Theory :
The Fast Fourier Transform (FFT) is a fast method of computing the Discrete Fourier Transform (DFT).
In the Radix-2 Decimation-in-Time (DIT) FFT:
	The input signal is divided first (decimated in time)
	The signal is split into even and odd indexed samples
	Smaller DFTs are computed
	Results are combined using butterfly operations
The Radix-2 DIT FFT requires the number of samples to be a power of 2:

N=2^m

This method reduces the computational complexity from:

DFT: N^2

FFT: N〖log⁡〗_2 N

Key Features of DIT-FFT :  
1) Decimation is done in time domain .

2) Input sequence is bit-reversed .
  
3) Output is in natural order  .
  
4) FFT is computed in log₂N stages.

# Algorithm :
1)Start the program

2)Define a discrete-time signal of length N=2^m

3)Rearrange the input in bit-reversed order

4)Apply FFT using Radix-2 DIT method

5)Compute the magnitude spectrum

6)Plot the FFT output

7)Stop the program

# MATLAB CODE:
<img width="969" height="1600" alt="image" src="https://github.com/user-attachments/assets/c623ff92-8726-4e38-858d-018af1d461d1" />

# OUTPUT GRAPH :
![WhatsApp Image 2026-04-10 at 6 47 09 PM](https://github.com/user-attachments/assets/7eefdd03-ae6c-47e5-9775-146a2f420dac)



# RESULT:
Thus, the Fast Fourier Transform of the given discrete-time signal was successfully computed using the Radix-2 Decimation-in-Time (DIT) FFT algorithm in MATLAB.


