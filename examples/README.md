# semiinf examples
Each folder contains example input file for the `semiinf.x` program.
The data files (`_hr.dat`, `_spnr.dat`) are included in the `examplexx/reference_out/` folder.
Also, one can open the ipython notebook `examplexx/examplexx.ipynb` and follow the pre- and post-processing scripts.

The tight-binding models used in the examples are generated either using the `wannier_tb.py` utility, or using the wannier90.x program after DFT calculations.

## List of examples
* example01: s orbitals on a cubic lattice. Bulk and surface band structures and DOS.
    * Tight-binding model is generated using `util/wannier_tb.py`
* example02: diamond (111) surface.
    * Tight-binding model is generated from first-principles using `Quantum ESPRESSO` and `Wannier90`.
