# CSMP 150 — 2026

Computational Modeling and Science course materials.

## Maximum entropy reweighting

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulrobustelli/CSMP_150_2026/blob/main/notebooks/maxent_die.ipynb)

[Maximum-entropy die notebook](notebooks/maxent_die.ipynb): solve for the probability distribution with a specified mean, or explore how the Lagrange multiplier changes the distribution. Includes live probability plots, Shannon entropy, and student exploration questions.

### Run in Google Colab

Click **Open in Colab**, then run the cells in order. The notebook enables Colab's interactive widget manager. To keep your changes, save a copy to your Google Drive.

### Run locally

Use Python 3 with Jupyter Notebook or JupyterLab. Install the notebook dependencies:

```sh
python -m pip install numpy scipy matplotlib ipywidgets
```

Open `notebooks/maxent_die.ipynb` and run the cells in order.

## Prinz potential and Markov state models

Open a notebook below, then choose **Runtime → Run all**. If Colab displays its standard external-notebook notice, choose **Run anyway** after reviewing the code. No Google Drive mount or external data files are required. Movie rendering in the 2D notebooks takes several minutes; set `EXPORT_MOVIES=False` in the movie cell to skip it. All times are Monte Carlo steps.

- [1D lecture and homework](notebooks/Prinz_Potential_Transfer_Operator.ipynb) · [Open in Colab](https://colab.research.google.com/github/paulrobustelli/CSMP_150_2026/blob/main/notebooks/Prinz_Potential_Transfer_Operator.ipynb)
- [1D instructor solutions](notebooks/Prinz_Potential_Transfer_Operator_Solutions.ipynb) · [Open in Colab](https://colab.research.google.com/github/paulrobustelli/CSMP_150_2026/blob/main/notebooks/Prinz_Potential_Transfer_Operator_Solutions.ipynb)
- [2D eight-well example: Prinz × double well](notebooks/Prinz_2D_Eight_Well_MSM.ipynb) · [Open in Colab](https://colab.research.google.com/github/paulrobustelli/CSMP_150_2026/blob/main/notebooks/Prinz_2D_Eight_Well_MSM.ipynb)
- [2D sixteen-well example: Prinz × Prinz](notebooks/Prinz_2D_MSM.ipynb) · [Open in Colab](https://colab.research.google.com/github/paulrobustelli/CSMP_150_2026/blob/main/notebooks/Prinz_2D_MSM.ipynb)

## PCA and TICA: a worked linear-algebra example

[Notebook](notebooks/PCA_TICA_Worked_Example.ipynb) · [Open in Colab](https://colab.research.google.com/github/paulrobustelli/CSMP_150_2026/blob/main/notebooks/PCA_TICA_Worked_Example.ipynb)

Work through centering, covariance entries, PCA eigenvectors, lagged covariance, the generalized TICA eigenproblem, whitening, projections, and implied timescales. A stationary two-coordinate Gaussian model separates a large fast fluctuation from a smaller slow fluctuation. Includes a reproducible 200,000-frame simulation, time-shuffle control, numerical checks, and exploration questions. Run all cells in standard Colab; no external data or package installation is required. Time is measured in simulation steps.
