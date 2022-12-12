sedfoam
=======

[![OpenFOAM v2206](https://img.shields.io/badge/OpenFOAM-v2206-brightgreen.svg)](https://openfoam.com/)

This repository provides the fluidicOscillator testcase from Holzmann, adapted by C. Bonamy for openfoam 2206.

Status
------

The adaptation of the testcase is done.

Pull requests are encouraged!

Features
--------

Blabla

Installation
------------

```bash
cd $WM_PROJECT_USER_DIR
git clone https://github.com/CyrilleBonamy/fluidicOscillator
cd fluidicOscillator
./run
oarsub -S ./launch.oar
```

Usage
-----

Use paraview in decompose mode to display the results

Developers
----------

*   Tobias Holzmann (he wrote the initial testcase, available for the openfoam.org versions)
*   Cyrille Bonamy (he only adapted the testcase for openfoam.com)

Acknowledgements
----------------

[OpenFOAM](https://www.openfoam.com) is the free, open source CFD
software developed primarily by OpenCFD Ltd since 2004.
The OpenFOAM trademark is owned by OpenCFD Ltd.

