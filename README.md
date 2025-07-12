# Code for: On the Constancy of a Maximal Emergent Speed in an Information-Based Geometry

This repository contains the complete code and computational environment to reproduce the results presented in the paper:

**Title:** On the Constancy of a Maximal Emergent Speed in an Information-Based Geometry
**Author:** Beau Leighton-Trudel
**Preprint:** (Link to arXiv once available)

---

## Description

The Jupyter Notebook `emergent-kinematics.ipynb` performs two independent analyses to validate that a constant maximal propagation speed is a necessary feature of a flat, information-theoretic geometry.

1.  A **static analysis** using the Density Matrix Renormalization Group (DMRG) to compute a geometric factor from the ground state of the 1D XXZ spin chain in its critical and gapped phases.
2.  A **direct dynamical analysis** of information propagation after a local quench in the analytically solvable 1D XX model, confirming a constant and universal speed.

## Repository Contents

- `emergent-kinematics.ipynb`: The main Jupyter Notebook containing all code for the simulations, analysis, and figure generation.
- `environment.yml`: The Conda environment file required to reproduce the exact computational environment used in the study.

## How to Reproduce Results

To reproduce the results and figures from the paper, please follow these steps:

1.  **Clone this repository:**
    ```bash
    git clone https://github.com/darkhorse131/emergent-kinematics.git
    cd emergent-kinematics
    ```

2.  **Create the Conda environment:** Use the provided `environment.yml` file to create a new Conda environment named `emergent-kinematics`. This will install all necessary libraries with the correct versions.
    ```bash
    conda env create -f environment.yml -n emergent-kinematics
    ```

3.  **Activate the environment:** Before running the notebook, you must activate the environment you just created.
    ```bash
    conda activate emergent-kinematics
    ```

4.  **Run the notebook:** Launch Jupyter Lab or Jupyter Notebook and execute the cells in `emergent-kinematics.ipynb`.
    ```bash
    jupyter lab
    ```

## Citation

If you use this code or the results from this work in your research, please cite both the paper and this code repository.

**Paper Citation:**
> (Placeholder for the BibTeX entry of your paper)

**Code Citation:**
> Beau Leighton-Trudel. (2025). *Code for: On the Constancy of a Maximal Emergent Speed in an Information-Based Geometry* (v1.0.0). Zenodo. [https://doi.org/10.5281/zenodo.YOUR_DOI_HERE](https://doi.org/10.5281/zenodo.YOUR_DOI_HERE)

## License
This project is licensed under the MIT License.
