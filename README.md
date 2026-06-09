# BAO-BGO Vortex Data

**Languages:** [中文](README_CN.md) | [English](README_EN.md)

This repository contains source data for the article:

**Emergent in-plane polar vortex state in a perovskite superlattice**  
Article DOI: https://doi.org/10.1103/t198-356c

The dataset includes the numerical data used for the main quantitative figures in the manuscript and Supplemental Material, together with selected representative structure files. Files are organized by figure number.

## Contents

- `Fig2/`: local polarization field, DFT-relaxed vortex structure, ELF data, and Born effective charge comparison data for main-text Fig. 2.
- `Fig3/`: field-dependent energy data for BAO/BGO and PTO/STO, plus temperature-dependent polarization-vector fields. Data for Supplemental Fig. S5 are also included in `Fig3/quiver_vs_T/`.
- `Fig4/`: zero-field, uniform-field, and local-field polarization configurations for main-text Fig. 4.
- `FigS1/`: CHGNet-versus-DFT relative-energy comparison data.
- `FigS2/`: energy and force validation data for machine-learning potentials trained with and without BEC information.
- `FigS3/`: temperature-dependent polarization data for BiAlO3 during heating and cooling.
- `FigS6/`: local polarization and octahedral-rotation vector fields before and after electric-field switching.
- `FigS7/`: representative BAO/BGO and PTO/STO structure snapshots under selected external electric fields.
- `FigS8/`: raw output used for the field-driven internal-energy and electric-enthalpy estimates.
- `FigS10/`: local polarization data and summary files from the BEC-based linear polarization estimate.

## File Formats

- `.xsf`: structure and vector-field data for visualizing local polarization or octahedral-rotation textures.
- `.vasp` / `CONTCAR`: VASP structure files.
- `.dat` / `.csv` / `.txt`: numerical source data for plotting.
- `.json`: summary information from polarization analysis.
- `.png` / `.pdf`: preview images or generated plots associated with the source data.

## Notes

This dataset is intended to support the quantitative figure data and representative structural results reported in the manuscript. Full large-scale molecular-dynamics trajectories are not included.

<details>
<summary>中文简介</summary>

本仓库包含论文 **Emergent in-plane polar vortex state in a perovskite superlattice** 的正文和补充材料主要定量作图数据，以及部分代表性结构文件。

论文 DOI：https://doi.org/10.1103/t198-356c

数据按图号整理：

- `Fig2/`：局域极化场、DFT 弛豫涡旋结构、ELF 数据和 Born effective charge 对比数据。
- `Fig3/`：BAO/BGO 与 PTO/STO 的外电场能量数据，以及不同温度下的极化矢量场。补充材料 Fig. S5 的数据也位于 `Fig3/quiver_vs_T/`。
- `Fig4/`：零外场、均匀外场和局域外场下的极化构型数据。
- `FigS1/` 至 `FigS10/`：补充材料中模型验证、温度演化、电场响应、结构快照和 BEC 极化估算等数据。

完整中文说明见 [README_CN.md](README_CN.md)。

</details>
