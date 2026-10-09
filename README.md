# RATR

<p align="center">
  <b>RATR: Training-Free Material Rebinding with Role-Aware Target–Reference Conditioning</b>
</p>

<p align="center">
  Official project page for <b>RATR</b>.
</p>

<p align="center">
  <b>Paper Coming Soon</b> &nbsp;|&nbsp;
  <b>Code Coming Soon</b>
</p>

---

## Overview

**RATR** is a training-free material rebinding framework built upon a frozen
two-image editor.

The key idea is to reorganize the target image and material reference into
role-specific visual conditions before generation. RATR aims to preserve the
geometry and identity of the target object while transferring the visible
material appearance of the reference.

The current repository serves as the project page and result gallery.
More qualitative results, comparisons, ablations, and implementation details
will be added progressively.

---

## Teaser

<p align="center">
  <img src="./assets/images/figure1.jpg" width="100%">
</p>

<p align="center">
  <i>
  RATR enables material rebinding across diverse targets and material
  references while preserving target geometry and identity.
  </i>
</p>

---

## Qualitative Comparison

<p align="center">
  <img src="./assets/images/comparison.jpg" width="100%">
</p>

<p align="center">
  <i>
  Qualitative comparison with representative material transfer and
  image-editing baselines.
  </i>
</p>

---

## Compared Methods

Our evaluation includes comparisons with the following methods and baselines:

- **DealMaTe**
- **Qwen-Image-Edit**
- **MARBLE**
- **MaterialFusion**
- **ZeST**
- **IP-Adapter SDXL + ControlNet**
- **IP-Adapter SD1.5 + ControlNet**
- **InstructPix2Pix + IP-Adapter**

Additional comparisons will be released with the full project page.

---

## More Results

More qualitative results will be added progressively, including:

- Diverse target categories
- Diverse material references
- One target with multiple materials
- One material across multiple targets
- Patterned and object-centric material references
- Metallic, glossy, translucent, rough, and textured materials
- Additional comparisons with previous methods
- Failure cases and challenging examples

---

## Ablation Study

Ablation results will be added for the two central mechanisms of RATR:

- **Target-side Role Decoupling**
- **Surface-Material Conditional Direction Routing (SM-CDR)**

We will also provide visualizations of different SM-CDR material-routing-share
profiles to illustrate the trade-off between material expression and
structural preservation.

---

## Quantitative Results

Quantitative evaluation and the complete benchmark protocol will be released
together with the paper.

The evaluation covers material similarity, semantic appearance, and
target-structure preservation under a common target-material benchmark.

---

## Code

**Code coming soon.**

The inference pipeline, evaluation scripts, and additional resources will be
released after the paper is ready for public release.

---

## Project Page

A full interactive project page is under construction.

It will include:

- Interactive qualitative results
- Target-material comparison gallery
- Full baseline comparisons
- Ablation visualizations
- Additional appendix results
- Paper and supplementary material
- Code and checkpoints

---

## Citation

BibTeX will be added upon publication.

```bibtex
@article{ratr,
  title   = {RATR},
  author  = {Anonymous},
  journal = {Under Review},
  year    = {2026}
}
