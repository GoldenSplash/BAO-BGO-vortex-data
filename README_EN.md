# Data Description

This dataset contains the data used to generate the main quantitative plots in the manuscript *Emergent in-plane polar vortex state in a perovskite superlattice* and its Supplemental Material, together with selected representative structure files. Article DOI: https://doi.org/10.1103/t198-356c. The files are organized by figure number.

## Directory description

- `Fig2/`
  - `polarization field/`: structure and local polarization-field data for the BiAlO3/BiGaO3 vortex state, used for main-text Fig. 2(a).
  - `5x5x2-DFT-relax/vortex-structure/`: representative vortex structure used for DFT relaxation.
  - `5x5x2-DFT-relax/ELF/`: ELF data used for main-text Fig. 2(b).
  - `BEC-compare/`: Born effective charge data for the vortex and ferroelectric states, together with source data for the BEC-difference contour map in main-text Fig. 2(c).

- `Fig3/`
  - `Efield-energy/BAGO-continuousE/`: energy data for BiAlO3/BiGaO3 under a continuous external electric field, used for main-text Fig. 3(a).
  - `Efield-energy/PSTO-continuousE/`: energy data for the PbTiO3/SrTiO3 reference system under a continuous external electric field, used for main-text Fig. 3(b).
  - `quiver_vs_T/`: polarization-vector fields at selected temperatures, used for main-text Fig. 3(c). The data for Supplemental Fig. S5 are also included in this folder.

- `Fig4/`
  - `a-Ex-0/`: zero-field reference configuration, used for main-text Fig. 4(a).
  - `b-Ex-0.8-partE1/`: polarization configuration under a local electric field applied to region 1, used for main-text Fig. 4(b).
  - `c-Ex-4.8-uniformE/`: polarization configuration under a uniform external electric field, used for main-text Fig. 4(c).
  - `d-Ex-3.8-partE2/`: polarization configuration under a local electric field applied to region 2, used for main-text Fig. 4(d).

- `FigS1/`
  - `dft_chgnet_energy/`: CHGNet-versus-DFT relative-energy comparison data for Supplemental Fig. S1.

- `FigS2/`
  - `no-bec/energy/` and `no-bec/force/`: energy and force validation data for the machine-learning potential trained without BEC information.
  - `bec/energy/` and `bec/force/`: energy and force validation data for the machine-learning potential trained with BEC information.

- `FigS3/`
  - `heat/` and `cool/`: temperature-dependent polarization data for BiAlO3 during heating and cooling.

- `FigS6/`
  - `P/`: local polarization-vector fields before and after electric-field switching.
  - `W/`: octahedral-rotation vector fields before and after electric-field switching.

- `FigS7/`
  - `BAGO/`: representative BiAlO3/BiGaO3 structure snapshots under selected external electric fields.
  - `PSTO/`: representative PbTiO3/SrTiO3 structure snapshots under selected external electric fields.

- `FigS8/`
  - `log-efield.out`: raw output used for the field-driven internal-energy and electric-enthalpy estimates.

- `FigS10/`
  - local polarization data, structure files, and summary information from the BEC-based linear polarization estimate, used for Supplemental Fig. S10.

## File formats

- `.xsf`: structure and vector-field data for visualizing local polarization or octahedral-rotation textures.
- `.vasp` / `CONTCAR`: VASP structure files.
- `.dat` / `.csv` / `.txt`: numerical source data for plotting.
- `.json`: summary information from the polarization analysis.
- `.png` / `.pdf`: preview images or generated plots associated with the source data.

## Notes

This dataset is intended to support the quantitative figure data and representative structural results reported in the manuscript. Full large-scale molecular-dynamics trajectories are not included.
