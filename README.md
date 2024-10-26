# PB-LJ EDL Model

This repository contains codes demonstrating the incorporation of van der Waals and soft repulsive interactions into a Poisson-Boltzmann framework, as developed in the study: [Incorporating Ion-Specific van der Waals and Soft Repulsive Interactions in the Poisson-Boltzmann Theory of Electrical Double Layers](http://dx.doi.org/10.1039/D3CP00745F).

## Software Requirements

- MATLAB

## Available Codes

1. **`ion_wall_code`**  
   This code solves for the potential and ionic concentration profiles inside an electrical double layer (EDL) considering ion-wall interactions. For a version of the ion-wall PB-LJ code without the approximation \((u^{iw}_{LJ}(L/2) \approx 0)\), please refer to the version in the `Comparison_Aluru` folder.

2. **`ion_ion_code_both.m`**  
   This code calculates the potential and ionic concentration profiles inside an EDL, including both ion-ion and ion-wall interactions.

3. **`Capacitance_NaF_Ag_111.m`**  
   This code plots differential capacitance curves for aqueous NaF solutions in contact with an Ag(111) electrode, comparing the results with experimental data (Valette, *J. Electroanal. Chem. Interfacial Electrochem.*, 1989, 269, 191–203).

4. **`Comparison_Aluru`**  
   This folder contains code to compute concentration profiles using our PB-LJ model for comparison with molecular dynamics results (Mashayak and Aluru, *J. Chem. Phys.*, 2017, 146, 044108).

5. **`sigma_epsilon_fitting.m`**  
   This code fits the Lennard-Jones (LJ) parameters for the polyatomic sulfate ion based on the LJ parameters for the constituent sulfur and oxygen atoms.

## Citation

If you use this code in your research, please cite the following:

```bibtex
@article{D3CP00745F,
  title  = "Incorporating Ion-Specific van der Waals and Soft Repulsive Interactions in the Poisson-Boltzmann Theory of Electrical Double Layers",
  author = "Seal, Aniruddha and Tiwari, Utkarsh and Gupta, Ankur and Govind Rajan, Ananth",
  journal = "Phys. Chem. Chem. Phys.",
  year = "2023",
  pages = "-",
  publisher = "The Royal Society of Chemistry"
}
