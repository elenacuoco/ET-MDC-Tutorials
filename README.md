# Einstein Telescope Mock Data Challenge Analysis
[ETworkshop2024] (https://agenda.infn.it/event/38405/) February 20-23th in Assisi

## Author
- Author: Elena Cuoco
- Contact: elena.cuoco@ego-gw.it

## Overview

This repository contains notebook  and scripts for analyzing the Mock Data Challenge 1 for the Einstein Telescope. The Einstein Telescope is a proposed third-generation gravitational-wave observatory that aims to significantly advance our understanding of 
the universe through the observation of gravitational waves.

The Mock Data Challenge involves simulating gravitational-wave signals and testing the capability of data analysis algorithms to detect and characterize these signals in the presence of noise.

## Materials reference
- https://gitlab.et-gw.eu/osb/div10/mdc-tutorial
- https://github.com/gw-odw/odw-2022/tree/main
- https://wdfpipe.gitlab.io/
- https://gwpy.github.io/docs/stable/
- https://pycbc.org/
- https://github.com/OverLordGoldDragon/ssqueezepy

## You will learn
- How to read and plot the data
- How to preprocess the signals
- How to whiten the data in frequency and time-domain
- How to map signals in Time-Frequency domain
- How to apply the matched filter

## Contents

1. **caches**: This directory contains the pointer to mock data generated for the challenge and the ffl file. 

2. **notebooks**: The main codebase for the analysis is located in this directory. It includes scripts for signal generation, noise simulation, and various algorithms for detecting and characterizing gravitational-wave signals.

3. **metadata**: It containd the list of injected signals

 

## Getting Started


1. Connect to  https://jhub-vre.cern.ch/
2. Use your ESCAPE AAI to connect
3. Load the WDF-Virgo environment 
4. Clone this repository


## Contributing

If you would like to contribute to the development of this analysis code, please follow the guidelines outlined in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

The ESCAPE VRE (https://vre-hub.github.io/) team and Enrique Garcia  enrique.garcia.garcia at cern.ch for his valuable support

 

---
 
