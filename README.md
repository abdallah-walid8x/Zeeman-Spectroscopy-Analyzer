# Zeeman-Spectroscopy-Analyzer
A program that models atomic energy level splitting and spectral lines
# Overview
This software simplifies the analysis of the Zeeman effect by automating the measurement of spectral line splitting and calculating fundamental physical constants such as the Bohr magneton and specific charge of the electron.

# Features
* User-friendly graphical interface with responsive layout
* Image input from file with preview
* Advanced spectral line analysis:
* Intelligent auto-ring detection with adaptive center point optimization
# Interactive measurement:
* View all measurements in a table
* Delete and redo individual measurements
* Real-time current and magnetic field display
* Magnetic field calibration
* Calculation of Bohr magneton and specific charge
# Data visualization:
* Plots
* Measurement tables
* Results summary
# Export options:
* Save plots as PNG/PDF
* Export data as CSV
* Copy results to clipboard
* Installation
* Clone this repository
# Install dependencies:
pip install -r requirements.txt
# Usage
# # Activate the virtual environment:

source .venv/bin/activate
# # Run the application:

python main.py
# # Using the application:

* Load Images: Click 'Open' to load spectral line images
 8Calibrate: Set up magnetic field calibration in the calibration window
* Take Measurements:
* Click to set center point
* For manual measurement: Click to measure inner, middle, and outer radii
* For auto-detection: Use the auto-detect buttons and define an annulus by clicking two points
* The software will automatically optimize the center point and detect the precise ring radius
* Review measurements in the table
* Delete and redo measurements if needed
* Analyze Results:
* View plots in the plot window
* Check calculated results in the results window
* Export Data:
* Save plots as PNG/PDF
* Export measurements to CSV
* Copy results to clipboard
