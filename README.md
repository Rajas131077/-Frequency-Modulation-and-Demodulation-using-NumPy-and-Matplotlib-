# -Frequency-Modulation-and-Demodulation-using-NumPy-and-Matplotlib-

__Aim:__

To implement and analyze frequency modulation (FM) using Python's NumPy and Matplotlib libraries.

__Apparatus Required:__ 

1. Software: Python with NumPy and Matplotlib libraries
   
2. Hardware: Personal Computer

 
__Theory:__

Frequency Modulation (FM) is a method of transmitting information over a carrier wave by varying its 
frequency in accordance with the amplitude of the input signal (message signal). The frequency of the carrier 
wave is varied according to the instantaneous amplitude of the message signal.

__Algorithm:__

1. Initialize Parameters: Set the values for carrier frequency, message frequency, sampling frequency, and 
   frequency deviation.
   
2. Generate Time Axis: Create a time vector for the signal duration.
    
3. Generate Message Signal: Define the message signal as a cosine wave.
    
4. Compute the Integral of the Message Signal: Calculate the integral of the message signal over time.
    
5. Generate FM Signal: Apply the FM modulation formula to obtain the modulated signal.
 
6. Plot the Signals: Use Matplotlib to plot the message signal, carrier signal, and modulated signal.

__Programme:__
// Parameters

Ac = 7.9;
Am = 15.8;
Fm = 306;
Fc = 3060;
Fs = 30600;
T = 0:1/Fs:2/Fm;

// Message signal em = Am * cos(2*%piFmT); subplot(3,1,1); plot(T, em); xtitle("Message Signal"); xgrid();

// Carrier signal ec = Ac * cos(2*%piFcT); subplot(3,1,2); plot(T, ec); xtitle("Carrier Signal"); xgrid(); // FM signal efm = Ac * cos( (2*%piFcT) + (B * sin(2*%piFmT)) ); subplot(3,1,3); plot(T, efm); xtitle("FM Signal"); xgrid();

TABULATION:

<img width="471" height="840" alt="image" src="https://github.com/user-attachments/assets/c48a0070-aeaa-49e3-ab79-eb766c719bcd" />


__Output:__

<img width="788" height="581" alt="image" src="https://github.com/user-attachments/assets/ad9bc638-2049-46f3-b864-07890380018c" />


__Result:__

thus the frequency modulation and demodulation using python is verified.
