# PreSense mmWave Package

[![Version](https://img.shields.io/pypi/v/ipyvolume.svg)](https://pypi.org/project/openradar/)
[![Documentation](https://readthedocs.org/projects/openradar/badge/?version=latest)](https://openradar.readthedocs.io/en/latest/?badge=latest)

This is PreSense team's implementation of TI mmwave radar DSP stack and some demos.
We are grateful for TI, TI's e2e forum and other people's help to make this happen.
Please star us if you like this repository and please consider citing this repo if you used it in your research.

The toolbox is modularized into separate steps
1. Reading raw ADC data.
2. Preprocessing data in DSP stack.
3. Utilizing preprocessed data for tracking, clustering and machine learning.
4. Different demo implementations from TI and our own explorations.

## Setup Enviroment

  conda create -n OpenRadar pip python=3.8

  conda activate OpenRadar

  pip install setuptools numpy pandas scipy matplotlib pyserial scikit_learn opencv-python  
