# Unscented Kalman Filter Project Starter Code
Self-Driving Car Engineer Nanodegree Program

## Overview

In this project we implement an Unscented Kalman Filter in order to predict and model simulated path. The UKF is well suited to handling non-linear models. The CTRV model used in this is non-linear and well suited to testing with the UKF.

Details on the algorithm and functions are available here;

[PDF] (https://pdfs.semanticscholar.org/5dd9/709902c328c8f8cc8aa0d02ce2f23dac41c7.pdf)



---

## Dependencies

* cmake >= v3.5
* make >= v4.1
* gcc/g++ >= v5.4

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./UnscentedKF path/to/input.txt path/to/output.txt`. You can find
   some sample inputs in 'data/'.
    - eg. `./UnscentedKF ../data/sample-laser-radar-measurement-data-1.txt output.txt`

## Visualizing the results

There is a Jupyter Notebook (python) file in the `/results` directory that can help visualize the output files from the `UnscentedKF` program. It provides a visual map and plots the NIS estimates against the 95% percentile


## Generating Additional Data

If you'd like to generate your own radar and lidar data, see the
[utilities repo](https://github.com/udacity/CarND-Mercedes-SF-Utilities) for
Matlab scripts that can generate additional data.
