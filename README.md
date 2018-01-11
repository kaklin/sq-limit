# Shockley-Queisser Limit Calculator
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/evcka/sq-limit/master)

Jupyter notebook recreting the calculations done by William Schockley and Hans J. Queisser for the detailed balance limit for the efficiency of a single junction solar cell. Originally published in 1961. 

Based heavily on the Mathematica script by Steve Byrnes, original available here: http://sjbyrnes.com/sq.pdf. 

The notebook goes through calculating the SQ limit for the standard ASTM G173 AM1.5 spectrum, with most of the difficult explanations taken from Steve's document. 

Further notebook sections look recalculate the detailed balance limit for lower irradiances, and for light sources other than the sun. 

## Instructions

### Binder
You can launch an interactive version of the notebook using Binder: [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/evcka/sq-limit/master)

### Local
Make sure you have the Jupyter notebook installed.

Tested with the following:

* Python 2.7
* matplotlib 2.1.0
* numpy 1.13.3
* scipy 1.0.0

Install using

`pip2 install requirements.txt`
