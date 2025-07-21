README.txt
===========

This repository contains molecular dynamics (MD) simulation data and analysis scripts related to the study of the SARS-CoV-2 wild-type and five of its variants. The data is organized into three main folders as follows:

1. MD_system/
--------------
This folder includes:
- Initial system configurations for MD simulations:
  - `.pdb` files: Atomic coordinates of the systems
  - `.psf` files: Structure/topology files for simulations
- Final MD snapshots in `.coor` format representing the configurations at the end of the production run.

Each file corresponds to either the SARS-CoV-2 wild-type or one of five selected variants.

2. Traj_analysis/
------------------
This folder contains scripts for analyzing MD trajectories:
- **VMD Tcl scripts**: Used for structure alignment, RMSD/RMSF analysis, hydrogen bond analysis, etc.
- **Python scripts**: Used for post-processing, data extraction, and plotting results from trajectory data.

These tools were used to analyze the dynamic interactions between ACE2 and the RBD of each SARS-CoV-2 system.

3. dcd_trajectory/
--------------------
This folder contains superimposed trajectory snapshots:
- `*.dcd` files: 200 ns MD trajectories (superimposed) of the ACE2-RBD complexes for all systems.
Each trajectory is processed and aligned to a reference structure to enable structural comparison across different variants.

----------------------------------
Please cite our work appropriately if you use this dataset or scripts. For further details or questions, feel free to contact the corresponding author.

