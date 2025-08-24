# Sampling-Studio-and-Signal-Reconstruction

## Introduction:
Sampling Theory Studio is a powerful desktop application designed to illustrate the concepts of signal sampling and recovery, emphasizing the importance and validation of the Nyquist rate. With its intuitive interface and comprehensive features, it allows users to load, visualize, sample, and recover analog signals seamlessly.

## Key Features:
* Sample & Recover: Users can load a mid-length signal, visualize it, sample it at different frequencies, and then use the sampled points to recover the original signal using the Whittaker–Shannon interpolation formula. The sampling frequency is displayed in either actual frequency or normalized frequency.
* Load & Compose: Signals can be loaded from files or composed using a built-in mixer. Users can add multiple sinusoidal signals of varying frequencies and magnitudes, and remove any components as needed.
* Additive Noise: Users have the option to add noise to the loaded signal with customisable signal-to-noise ratio (SNR) levels. The program visually demonstrates the dependency of noise effects on signal frequency.
* Real-time Processing: Sampling and recovery are performed in real-time, automatically updating upon user changes without the need for manual refresh.
* Resizable Interface: The application features a user-friendly interface that can be easily resized without disrupting the user experience.
* Different Sampling Scenarios: SignalSampler+ includes at least three synthetic signals generated through its Composer, addressing various testing scenarios to demonstrate the versatility and effectiveness of the application.

## Requirements
* Python 3.x
* PyQt5
* PyQtGraph
* NumPy
* Pandas
* ReportLab

## Installation
* Clone the repository:
```
git clone <https://github.com/Salma-me/Sampling-Theory-Studio.git>
```
* Install dependencies:
```
pip install -r requirements.txt
```
* Run the application:
```
python main.py
```
