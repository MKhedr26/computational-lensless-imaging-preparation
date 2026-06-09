# Computational Lensless Imaging Preparation

This repository is a focused Python/Jupyter preparation portfolio for computational lensless imaging research.

The notebooks build from Fourier-optics foundations toward scalar diffraction propagation, holography, phase retrieval, ptychography, and structured illumination / compressive-imaging basics. They were prepared as part of my transition from optical metrology R&D toward computational optical imaging.

These notebooks are not presented as original research. Their purpose is to document focused preparation, implementation practice, and conceptual understanding of the forward models and reconstruction ideas used in lensless imaging.

## Contents

| Notebook                                     | Topic                                                                                                              |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| `01_fourier_transform_foundations.ipynb`     | Centered FFT conventions, spatial/frequency axes, aperture and diffraction examples                                |
| `02_angular_spectrum_propagation.ipynb`      | Angular-spectrum propagation, coherent field propagation, transfer functions                                       |
| `03_fresnel_propagation.ipynb`               | Fresnel propagation, quadratic phase approximation, diffraction-regime intuition                                   |
| `04_digital_holography.ipynb`                | Off-axis digital holography, reference-wave encoding, Fourier sideband filtering                                   |
| `05_phase_retrieval_er_hio.ipynb`            | ER/HIO phase retrieval, support constraints, intensity-only reconstruction                                         |
| `06_ptychography_pie_reconstruction.ipynb`   | Ptychographic forward model, scan overlap, Fourier-modulus projection, PIE reconstruction                          |
| `07_structured_illumination_basics.ipynb` | Structured illumination as measurement diversity, (y = Ax), least-squares reconstruction, sparsity-prior intuition |

## Motivation

Computational lensless imaging combines optical forward models with numerical reconstruction. Instead of relying only on conventional imaging optics, information about the object can be encoded through diffraction, interference, scan diversity, structured illumination, or speckle patterns, and then recovered computationally.

The goal of this portfolio is to build the foundations needed to understand topics such as:

* scalar diffraction and wave propagation;
* intensity-only measurements and phase retrieval;
* ptychographic reconstruction;
* structured illumination and measurement diversity;
* basic inverse-problem and compressive-imaging ideas.

## Tools

* Python
* NumPy
* Matplotlib
* Jupyter notebooks

## Notes

The notebooks are educational and exploratory. They are intended to show preparation for research in computational optical imaging, not to claim novelty or completeness.
