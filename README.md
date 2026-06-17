# Generalized Parallel Axis Theorem for Rotational Inertia

This repository contains the computational part of our General Physics I project.

## Paper

A. R. Abdulghany, "Generalization of parallel axis theorem for rotational inertia,"
American Journal of Physics, Vol. 85, No. 10, pp. 791--795, 2017.
DOI: 10.1119/1.4994835

## Project Goal

The purpose of this project is to understand, reproduce, and computationally verify the generalized parallel-axis theorem for rotational inertia.

## Files

* `Physics_project_final.ipynb`
  Python notebook containing the computational verification and numerical simulations.

* `Physics_Group_Project_Report_Final.docx`
  Final written report version.

## What the Code Does

1. Implements the inertia tensor for a three-dimensional point-mass system.
2. Implements the symmetric matrix operator `[(A, B)]` used in the original paper.
3. Verifies the generalized tensor form of the parallel-axis theorem.
4. Visualizes the change of (I'_{zz}) as the reference point moves.
5. Applies the tensor translation formula to compound structural objects.
6. Reproduces the cuboid-cylinder sample calculation from Abdulghany's paper.
7. Performs Monte Carlo numerical verification using randomly sampled mass points.

## Requirements

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## How to Run

Open the notebook:

```text
Physics_project_final.ipynb
```

Then run all cells from top to bottom in Jupyter Notebook or VS Code.

## Main Result

The reproduced sample calculation gives:

```text
I'/(mu r^2) =
[[100.033741,   0.000000,   0.000000],
 [  0.000000,  64.197310, -26.394051],
 [  0.000000, -26.394051,  40.073893]]
```

This agrees with the rounded result reported in the original paper up to rounding error.

## Note

The original paper PDF is not included in this repository. Please refer to the DOI above.
