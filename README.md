This software package is a collection of MATLAB functions for simulating several ultrasound beamforming methods and a new developed speed-of-sound (SOS) estimation method using the Field II simulation software [1]. Currently, it supports the simulation of three beamforming algorithms: Synthetic Aperture Sequential Beamforming (SASB) [2], Dynamic Receive Beamforming (DRF), and Single Receive-focused Delay-and-Sum Beamforming (srDAS). See [3] for details. To execute the modules provided in this package, a correct installation of the Field II package is required.

This package consists of four types of functions:

### Per-Channel Radio Frequency (RF) data generation functions

These scripts are listed in the sub-folder 'RF_data_generation'. Two per-channel RF data generation scripts are provided. The 'RF_generate.m' file simulates a focused transmission in a one-layer medium; whereas the 'RF_twoLayers.m' file simulates a focused transmission in a two-layer phantom with two distinct SOSs. This is achieved by compensating for the time-of-flight (TOF) difference in a one-layer and two-layer phantom.

### Beamforming Functions
Three beamforming methods are included in the package: the DRF method, the SASB method, and the srDAS method. These beamforming functions are located in the folder 'beamforming_function'. The output of these three beamforming methods using a point spread function phantom is shown in Figure 1.
[Figure 1](output_beamforming.png)

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](http://www.ece.ubc.ca/~manyoum/dual_stage_sos/output_beamforming.png)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/manyouma/dual_stage_sos/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
