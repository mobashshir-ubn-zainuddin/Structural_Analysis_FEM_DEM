# FEM_DEM_Structural_Analysis

A small collection of finite element method (FEM) and discrete element method (DEM) teaching notebooks, plus a formatted HTML/PDF reference for the core formulations.

## Contents

- [1D_Structural_Analysis_FEM.ipynb](1D_Structural_Analysis_FEM.ipynb) - 1D axial bar FEM example with preprocessing, stiffness assembly, boundary conditions, solution, and post-processing.
- [2D_FEM.ipynb](2D_FEM.ipynb) - 2D plane stress FEM example using Constant Strain Triangle (CST) elements.
- [DEM_2d.ipynb](DEM_2d.ipynb) - 2D DEM simulation of particles under gravity with spring-dashpot contact forces.
- [FEM_DEM_Complete_Formulation.html](FEM_DEM_Complete_Formulation.html) - Interactive HTML reference covering FEM and DEM theory, derivations, and visual diagrams.
- [FEM_DEM_Complete_Formulations.pdf](FEM_DEM_Complete_Formulations.pdf) - PDF version of the formulation reference.

## What This Repository Covers

### FEM

The FEM notebooks show the standard workflow for structural analysis:

1. Discretize the domain into elements.
2. Define material and geometric properties.
3. Build local element stiffness matrices.
4. Assemble the global stiffness matrix.
5. Apply boundary conditions and external loads.
6. Solve for nodal unknowns.
7. Post-process displacements, strains, stresses, and reactions.

The repository includes both 1D and 2D examples:

- The 1D notebook solves an axially loaded bar.
- The 2D notebook solves a plane stress plate problem using CST triangles.

### DEM

The DEM notebook demonstrates particle-based simulation with:

- Particle-particle contact detection.
- Particle-wall contact handling.
- Linear spring-dashpot force models.
- Explicit time integration.
- Energy and motion post-processing.

The HTML formulation file also contains a live visual demo for FEM/DEM concepts.

## Recommended Environment

The notebooks were written for a standard Python scientific stack:

- `numpy`
- `matplotlib`
- `jupyter` or `notebook`

If you want to run the notebooks locally, install the dependencies first:

```bash
pip install numpy matplotlib jupyter
```

## How To Use

1. Open the notebook you want to run in Jupyter or VS Code.
2. Run the cells from top to bottom.
3. Review the printed intermediate values and plots.
4. Use the HTML file for a more visual explanation of the formulas.

## Suggested Order

If you are studying the topic, start with:

1. [1D_Structural_Analysis_FEM.ipynb](1D_Structural_Analysis_FEM.ipynb)
2. [2D_FEM.ipynb](2D_FEM.ipynb)
3. [DEM_2d.ipynb](DEM_2d.ipynb)
4. [FEM_DEM_Complete_Formulation.html](FEM_DEM_Complete_Formulation.html)

## Notes

- The FEM notebooks are educational examples, not production solvers.
- The DEM notebook uses simplified contact laws suitable for demonstration and learning.
- The HTML reference is useful for revision because it groups the mathematical formulation and visual explanation in one place.

## Files At A Glance

| File | Purpose |
| --- | --- |
| `1D_Structural_Analysis_FEM.ipynb` | 1D bar FEM example |
| `2D_FEM.ipynb` | 2D CST plane stress FEM example |
| `DEM_2d.ipynb` | 2D particle-based DEM example |
| `FEM_DEM_Complete_Formulation.html` | Interactive FEM/DEM formula reference |
| `FEM_DEM_Complete_Formulations.pdf` | PDF reference document |

## License

No license file is currently present in this folder. Add one if you want to define usage terms.
