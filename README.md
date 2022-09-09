# Battery-SOC-Estimation
This is the battery soc estimation code for lab EE401

A simple and naive battery modelisation + Kalman filter for state of charge (SoC) estimation

## Python implementation
python3 implementation of an extended Kalman filter for state of charge (SoC) estimation of a simulated lithium battery. 

To run it for extended kalman filters results just launch:
```sh
$> python Python/main.py
```

To run it for kalman filters results just launch:
```sh
$> python Python/main.py
```
Or use any python IDE (spyder/ jupyter notebook) and run the above mentioned files.

## Files:
    - cell.py : It implements the battery model as a python class with properties and methods to
update and set/get the battery properties. It can be run to produce the OCV vs SOC plot.

## Dependencies:
    - python3
    - numpy
    - matplotlib
