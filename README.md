# fMRI Image Reconstruction with DDIM-based Refinement

This repository contains a reproduction of an existing fMRI-to-image reconstruction
pipeline, along with experimental work exploring DDIM-based refinement of the
reconstructed images.

## Overview
The base pipeline reconstructs visual stimuli from fMRI signals recorded from
visual cortex regions using a GAN-based architecture with reconstruction,
perceptual, and adversarial losses. This code was reproduced to study and
understand generative modeling applied to neural data.

## My Contribution
- Ran and analyzed an existing fMRI-to-image reconstruction pipeline
- Fine-tuned selected preprocessing and inference parameters
- Implemented DDIM-based refinement on the generated images
- Conducted experiments with different DDIM sampling steps
- Evaluated results using qualitative visual inspection and PSNR/SSIM metrics

## Results
Representative qualitative samples and evaluation metrics from the DDIM
experiments are included directly in the `fmri_ddim.ipynb` notebook. Full
outputs are not included due to size constraints.

