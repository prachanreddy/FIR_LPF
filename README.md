# ECG Signal Denoising using FIR Low-Pass Filter

This project implements a 35-tap FIR low-pass filter for ECG signal denoising using MATLAB and Verilog HDL. The filter removes high-frequency muscle artifacts while preserving important ECG waveform characteristics.

## Features

* FIR low-pass filter designed using Hanning window
* ECG signal filtering and denoising
* Frequency and phase response analysis
* Time-domain and frequency-domain visualization
* Signal-to-Noise Ratio (SNR) evaluation
* IEEE-754 floating-point hardware implementation in Verilog

## Filter Specifications

* Sampling Frequency: 360 Hz
* Cutoff Frequency: 40 Hz
* Filter Length: 35 taps
* Window Type: Hanning Window

## MATLAB Functionality

The MATLAB script:

* Loads noisy and clean ECG datasets
* Designs the FIR filter
* Generates magnitude and phase response plots
* Filters the ECG signal using zero-phase filtering
* Compares noisy, filtered, and clean ECG signals
* Computes SNR improvement

## Verilog Implementation

The hardware implementation includes:

* IEEE-754 Floating Point Adder
* IEEE-754 Floating Point Multiplier
* FIR Convolution Testbench

The Verilog output was verified against MATLAB results and showed close waveform similarity.

## Results

The designed filter successfully reduces high-frequency muscle noise from the ECG signal while maintaining waveform integrity.

## Tools Used

* MATLAB
* Verilog HDL
* Vivado/FPGA Synthesis Tools

## Authors

* Prachan Reddy A J
* Priyanshu Raj Singh
* Dhairya Shivhare

