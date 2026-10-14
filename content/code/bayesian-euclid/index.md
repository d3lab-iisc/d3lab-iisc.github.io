---
title: Bayesian-EUCLID
summary: Discovering hyperelastic material laws with uncertainties, using stress-unsupervised Bayesian learning. Python · GPL-3.0
date: 2022-06-22 # first released on GitHub
show_date: false

tags:
  - Python
  - EUCLID
  - Hyperelasticity

# Buttons shown on the card and on this page
url_code: https://github.com/EUCLID-code/EUCLID-hyperelasticity-bayesian
links:
  - name: Paper
    url: https://doi.org/10.1016/j.cma.2022.115225
  - name: Docs
    url: https://euclid-code.github.io/EUCLID-hyperelasticity-bayesian/mkdocs/site/

# Card / header image: featured.jpg in this folder
image:
  caption: 'Bayesian-EUCLID framework'
  focal_point: Smart
---

Bayesian-EUCLID (Efficient Unsupervised Constitutive Law Identification and Discovery) discovers interpretable hyperelastic material models, with quantified uncertainties, from full-field displacement data and reaction forces, without stress data. A large library of constitutive features is combined with sparsity-promoting spike-and-slab priors, and the physics-constrained likelihood is based on linear momentum balance. Gibbs sampling then gives parsimonious models as posterior distributions with epistemic and aleatoric uncertainties.

Compared to the earlier EUCLID framework, it discovers material models about 100 times faster while using far less data. The repository includes the quasi-static and dynamic FE benchmark data used in the paper (Arruda-Boyce, Gent-Thomas, Haines-Wilson, Holzapfel, Isihara, Neo-Hookean, Ogden).

### Quick start

```bash
git clone https://github.com/EUCLID-code/EUCLID-hyperelasticity-bayesian.git
cd EUCLID-hyperelasticity-bayesian/drivers
python main_hss.py ArrudaBoyce high
```

Requires Python with `numpy`, `scipy`, `torch`, `pandas`, `matplotlib`, `seaborn` and `scikit-learn`. See the [online documentation](https://euclid-code.github.io/EUCLID-hyperelasticity-bayesian/mkdocs/site/) for a file-by-file explanation and a worked example, and the [EUCLID project website](https://euclid-code.github.io/) for related codes.

### Citation

If you use this code, please cite the paper:

> A. Joshi, P. Thakolkaran, Y. Zheng, M. Escande, M. Flaschel, L. De Lorenzis, S. Kumar. Bayesian-EUCLID: Discovering hyperelastic material laws with uncertainties. *Computer Methods in Applied Mechanics and Engineering*, 398, 115225 (2022). [doi:10.1016/j.cma.2022.115225](https://doi.org/10.1016/j.cma.2022.115225)

Typo corrections to the published article are listed [here](https://github.com/EUCLID-code/EUCLID-hyperelasticity-bayesian/blob/main/bayesian-euclid-corrections.pdf).
