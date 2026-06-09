# 数据说明

本数据集包含论文 *Emergent in-plane polar vortex state in a perovskite superlattice* 中正文和补充材料主要定量作图所用的数据，以及部分关键结构文件。

论文 DOI：[https://doi.org/10.1103/t198-356c](https://doi.org/10.1103/t198-356c)

数据按图号整理。

## 目录说明

- `Fig2/`
  - `polarization field/`：BiAlO3/BiGaO3 涡旋态的结构与局域极化场数据，用于正文 Fig. 2(a)。
  - `5x5x2-DFT-relax/vortex-structure/`：用于 DFT 弛豫的代表性涡旋结构文件。
  - `5x5x2-DFT-relax/ELF/`：ELF 数据文件，用于正文 Fig. 2(b)。
  - `BEC-compare/`：涡旋态与铁电态的 Born effective charge 数据，以及 BEC 差值的等值图源数据，用于正文 Fig. 2(c)。

- `Fig3/`
  - `Efield-energy/BAGO-continuousE/`：BiAlO3/BiGaO3 在连续外电场下的能量变化数据，用于正文 Fig. 3(a)。
  - `Efield-energy/PSTO-continuousE/`：PbTiO3/SrTiO3 参考体系在连续外电场下的能量变化数据，用于正文 Fig. 3(b)。
  - `quiver_vs_T/`：不同温度下的极化矢量场数据，用于正文 Fig. 3(c)。补充材料 Fig. S5 的温度演化数据也放在该文件夹中。

- `Fig4/`
  - `a-Ex-0/`：零外场参考构型数据，用于正文 Fig. 4(a)。
  - `b-Ex-0.8-partE1/`：局域外电场区域 1 条件下的极化构型数据，用于正文 Fig. 4(b)。
  - `c-Ex-4.8-uniformE/`：均匀外电场条件下的极化构型数据，用于正文 Fig. 4(c)。
  - `d-Ex-3.8-partE2/`：局域外电场区域 2 条件下的极化构型数据，用于正文 Fig. 4(d)。

- `FigS1/`
  - `dft_chgnet_energy/`：CHGNet 与 DFT 相对能量对比数据，用于补充材料 Fig. S1。

- `FigS2/`
  - `no-bec/energy/`、`no-bec/force/`：未包含 BEC 信息的机器学习势能量和力验证数据。
  - `bec/energy/`、`bec/force/`：包含 BEC 信息的机器学习势能量和力验证数据。

- `FigS3/`
  - `heat/`、`cool/`：BiAlO3 加热和冷却过程中的极化随温度变化数据。

- `FigS6/`
  - `P/`：外电场切换前后的局域极化矢量场数据。
  - `W/`：外电场切换前后的八面体旋转矢量场数据。

- `FigS7/`
  - `BAGO/`：BiAlO3/BiGaO3 在不同外电场下的代表性结构快照。
  - `PSTO/`：PbTiO3/SrTiO3 参考体系在不同外电场下的代表性结构快照。

- `FigS8/`
  - `log-efield.out`：场驱动过程中能量与电焓估算相关的原始输出数据。

- `FigS10/`
  - BEC 线性近似得到的局域极化分布数据、结构文件和汇总文件，用于补充材料 Fig. S10。

## 文件格式

- `.xsf`：结构和矢量场数据，可用于可视化局域极化或八面体旋转纹理。
- `.vasp` / `CONTCAR`：VASP 结构文件。
- `.dat` / `.csv` / `.txt`：作图用数值数据。
- `.json`：极化分析的汇总信息。
- `.png` / `.pdf`：部分数据对应的预览图或作图结果。

## 备注

该数据集主要用于支持论文中各图的定量结果和关键结构展示。完整的大规模分子动力学轨迹未包含在本数据集中。
