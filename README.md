# preCICE2022Material

Material for the talk "From low-order to high-order coupling schemes" given at preCICE Workshop 2022

For running the notebooks, you need preCICE and the python-bindings installed on your system (v2.3 or later). To use the experimental API with waveform relaxation, you have to use https://github.com/precice/precice/pull/1187 together with a slightly modified version of the python-bindings from https://github.com/BenjaminRodenberg/python-bindings/tree/waveform-API.

Use `jupyter nbconvert --to python *.ipynb` to convert the notebooks to normal python files. You can then just run them from the terminal.

There are three config files:

* `precice-config-init-serial.xml`: Normal serial implicit coupling from preCICE v2.3.
* `precice-config-both-init.xml`: Normal parallel implicit coupling from preCICE v2.3.
* `precice-config-experimental-both-init.xml`: Experimental parallel implicit coupling from  https://github.com/precice/precice/pull/1187.
