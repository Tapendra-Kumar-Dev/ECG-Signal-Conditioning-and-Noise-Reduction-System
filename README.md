# ECG Signal Conditioning and Noise Reduction System

## Overview

This project implements an ECG signal conditioning chain in LTspice to amplify low-amplitude ECG signals and reduce unwanted noise components.

## Components

* Instrumentation Amplifier
* 50 Hz Twin-T Notch Filter
* 2nd Order Sallen-Key Low-Pass Filter (100 Hz)
* Final Gain Stage

## Objectives

* Amplify millivolt-level ECG signals
* Remove 50 Hz power-line interference
* Reduce 300 Hz high-frequency noise
* Analyze system performance using transient and frequency-domain simulations

## Tools Used

* LTspice

## Results

The final system successfully amplifies the ECG signal while suppressing both power-line and high-frequency noise. Replacing the first-order low-pass filter with a second-order Sallen-Key filter improved attenuation of the 300 Hz noise component.
