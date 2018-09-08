# LabVIEW_machinerybalancing
LabVIEW program for balancing rotating machinery

This tool was used by the department of Navy for balancing rotating equipment. Developed fully in LabVIEW 2010. Tool requires data
to be pulled from a National Instruments DAQ (Data Acquisition device). Tachometer required, and at least one accelerometer needed to run.

Features:
- Accelerometer calibration tool
- Binary tree search algorithm for determining best weight to place in each location

To use:
- create a spreadsheet file indicating the configuration and name of accelerometer locations and weights available for balancing
- Load file into LabVIEW program
- Run calibration on all accelerometers
- Run program, and use polar plots to track movement of magnitude and phase

Possible improvements:
Add averaging to the phase calculation by averaging the complex number.
