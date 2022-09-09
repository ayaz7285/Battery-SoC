# Battery-SOC-Estimation
This is the battery soc estimation code for lab EE401

A simple and naive battery modelisation + Kalman filter for state of charge (SoC) estimation

## Python implementation
python3 implementation of an extended Kalman filter for state of charge (SoC) estimation of a simulated lithium battery. 

To run it for extended kalman filters results just launch:
```sh
$> python Python/main.py
```

Or use any python IDE (spyder/ jupyter notebook) and run the above mentioned files.

## Files:
* **cell.py:** It implements the battery model as a python class with properties and methods to update and set/get the battery properties. It can be run to produce the OCV vs SOC plot.
* **extended_kalman_filter.py:** It implements the extended Kalman filter with the methods predict and update.
* **polynomial.py:** It has a polynomial class that outputs f(x) where f(x) is a polynomial function and x is an input. It can also give the derivative of that function
* **main.py:** It runs the program and contains the flow of the code. Contains all the function calls and object creation of all the classes to instantiate their object with initial values.
* **experiment.py:** It is the flow of the experiment which simulates the battery soc result.
    
## Dependencies:
    - python3
    - numpy
    - matplotlib
