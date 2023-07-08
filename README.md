# fft
# Image Processing Code for Power Spectral Density (PSD) Analysis to estimate a pore size

This code processes an image to compute the Power Spectral Density (PSD) using Fourier Transform. It performs the following steps:

1. Loads the input image ('2_kN_Middle.png').
2. Converts the image to grayscale.
3. Subtracts the mean of the signal from the grayscale image.
4. Performs a 1D FFT (Fast Fourier Transform) on the grayscale image.
5. Sets the DC component to zero.
6. Computes the PSD for selected rows in the FFT spectrum.
7. Computes the corresponding wavelengths based on the image dimensions.
8. Plots the PSD with the wavelength for the selected rows.

## Prerequisites

The following dependencies are required to run the code:

- NumPy
- Matplotlib
- pylatex

## Usage

1. Ensure that the required dependencies are installed.
2. Place the input image you want to analyze in the same directory as the code.
3. Run the code to generate the PSD plot.
4. The output plot is saved as 'psd_plot.pdf'.

## Example

You can modify the code to select different rows for PSD computation or change the input image. The code provides an example for plotting two selected rows ('50' and '100').

