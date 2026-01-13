---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Hetero-EUCLID paper published in CMAME (January-2026)
# subtitle: ""
summary: (Hetero-EUCLID) Interpretable model discovery for heterogeneous hyperelastic materials using stress-unsupervised learning
authors:  
  - Kanhaiya Lal Chaurasiya
  - Saurav Dutta
  - Siddhant Kumar
  - Akshay Joshi

tags: ''

categories: 
  - News

date: '2026-01-12T00:00:00Z'

lastmod: '2026-01-12T00:00:00Z'

featured: false

draft: false


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: true


# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# {{% callout note %}}
# For more details, please visit:
# - ### [Cargo-Hyperloop Mobility System]({{< relref "/project/cargo-hyperloop" >}})
# {{% /callout %}}
---
{{< figure src="featured.jpg">}}


### Abstract
We propose a computational framework, **Hetero-EUCLID**, for segmentation and parameter identification to characterize the full hyperelastic behavior of all constituents of a heterogeneous material. In this work, we leverage the <ins>Bayesian-EUCLID (Efficient Unsupervised Constitutive Law Identification and Discovery)</ins> framework to efficiently solve the heterogenized formulation through parsimonious model selection using sparsity-promoting priors and Monte Carlo Markov Chain sampling. We utilize experimentally observable 3D surface displacement and boundary-averaged force data generated from Finite Element simulations of non-equi-biaxial tension tests on heterogeneous specimens. The framework broadly consists of two steps: residual force-based segmentation and constitutive parameter identification. We validate and demonstrate the ability of the proposed framework to segment the domain and characterize the constituent materials on various types of thin square heterogeneous domains. We validate the framework's ability to segment and characterize materials with multiple levels of displacement noises and non-native mesh discretizations, i.e., using different meshes for the forward FE simulations and the inverse EUCLID problem. This demonstrates the applicability of the Hetero-EUCLID framework in Digital Image/Volume Correlation-based experimental scenarios. Furthermore, the proposed framework performs successful segmentation and material characterizations based on data from a single experiment, thereby making it viable for rapid, interpretable model discovery in domains such as aerospace and defense composites and for characterization of selective tissue stiffening in medical conditions such as *fibroatheroma*, *atherosclerosis*, or cancer. 


{{< cite page="/publication/chaurasiya-hetero-euclid-2025" view="4" >}}

