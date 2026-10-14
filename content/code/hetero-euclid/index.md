---
title: Hetero-EUCLID
summary: Interpretable model discovery for heterogeneous hyperelastic materials using stress-unsupervised learning. Python · GPL-3.0
date: 2026-09-30
show_date: false

tags:
  - Python
  - EUCLID
  - Hyperelasticity

# Buttons shown on the card and on this page
url_code: https://github.com/d3lab-iisc/Hetero-EUCLID
links:
  - name: Paper
    url: https://doi.org/10.1016/j.cma.2026.118729
  - name: Zenodo
    url: https://doi.org/10.5281/zenodo.23359466 # software archive, latest release

# Card / header image: featured.jpg in this folder
image:
  caption: 'Hetero-EUCLID workflow'
  focal_point: Smart
---

Hetero-EUCLID segments a heterogeneous specimen into its material regions and discovers an interpretable hyperelastic model for each region, using only full-field displacements and boundary reaction forces, without stress data. It builds on [Bayesian-EUCLID](https://github.com/EUCLID-code/EUCLID-hyperelasticity-bayesian) and works in two steps: residual force-based segmentation, then constitutive parameter identification with a sparsity-promoting spike-and-slab prior sampled by MCMC.

The repository includes example FE datasets (cross-shaped inclusion and split domain) for reproducing the results in the paper.

### Quick start

```bash
git clone https://github.com/d3lab-iisc/Hetero-EUCLID.git
cd Hetero-EUCLID
pip install -r requirements.txt
cd drivers
python main_hss_hetero_euclid.py Type1_Cross_Shaped_Inclusion none
```

See the [repository README](https://github.com/d3lab-iisc/Hetero-EUCLID#readme) for the conda environment, noise levels and output files.

### Citation

If you use this code, please cite the paper:

> K. L. Chaurasiya, S. Dutta, S. Kumar, A. Joshi. Hetero-EUCLID: Interpretable model discovery for heterogeneous hyperelastic materials using stress-unsupervised learning. *Computer Methods in Applied Mechanics and Engineering*, 452, 118729 (2026). [doi:10.1016/j.cma.2026.118729](https://doi.org/10.1016/j.cma.2026.118729)

To cite the software itself, use the archived release on Zenodo: [10.5281/zenodo.23359467](https://doi.org/10.5281/zenodo.23359467).
