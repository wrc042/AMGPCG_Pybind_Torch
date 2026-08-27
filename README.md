# AMGPCG_Pybind

This is the pybind for the AMGPCG solver in [yuchen-sun-cg/lfm](https://github.com/yuchen-sun-cg/lfm) using pytorch extension. A wrapper for warp is also provided in amgpcg_pybind/warp.py. 

---

This code is used by [LFM](https://github.com/yuchen-sun-cg/lfm), [VPFM](https://github.com/pfm-gatech/VPFM), [WaveCouple](https://github.com/swang3081/Hamiltonian-Two-Way-Coupling-of-Nonlinear-Waves-and-3D-Flows).

## Installation

To install, run:

```bash
pip install .
```

Make sure that you always import torch first before import amgpcg_pybind.
