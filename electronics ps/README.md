# electroic_intrahall_ps
README
This repository contains a Python code that can be used to perform signal processing tasks using various functions from the scipy library. The code is designed to:

Read in signals from files
Band limit the inputs using scipy.butter
Perform amplitude modulation
Merge the three waveforms
Separate the three waveforms using a bandpass filter
Perform demodulation using a square law demodulator

Requirements

Python 3.5 or higher
numpy and scipy libraries

Installation

Clone this repository: git clone https://github.com/your_username/signal-processing.git
Install the necessary libraries: pip install -r requirements.txt

Usage

Run the main.py file
Follow the prompts to input the necessary information, including the filename of the signal, the desired cutoff frequency, and the carrier frequency for modulation.
The program will then perform band limiting on the input signals, perform amplitude modulation, merge the three waveforms, separate the waveforms using a bandpass filter, and perform demodulation using a square law demodulator.
The resulting waveforms will be plotted and saved to a file.

Code Structure

solutiong.py: This file contains functions for reading in signals from files, performing band limiting, performing amplitude modulation, merging waveforms, separating waveforms using a bandpass filter, and performing demodulation using a square law demodulator.
