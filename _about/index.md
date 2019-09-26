---
title: "About MSK-ACCESS"
permalink: /about/index/
excerpt: "About MSK-ACCESS."
last_modified_at: 2018-05-11T15:12:19-04:00
redirect_from:
  - /theme-setup/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
---
[MSK-ACCEES](https://github.com/msk-access) is being developed at MSKCC as part of CMO MSK-ACCESS team for analysis of MSK-ACCESS datasets.


The MSK-ACCESS project is focused on incorporating methods of "collapsing" a bam file across reads that come from the same initial cfDNA molecule, as determined by the Unique Molecular Indices included during library preparation.

We use Toil and CWL to combine various tools into a pipeline for collapsing UMI-tagged DNA molecules.

We draw on the work done by the Platform Informatics team at MSKCC in building Roslin and the IMPACT pipeline.


These tools will be used for:

- Ad-hoc analysis
- Creating workflows and running workflows
- Running workflows in multiple environments including:
  - High Performance Computing Clusters (SGE, LSF)
  - MacOS
  - Cloud Enviornment

- - - -

## Contributors:

- [Ronak H Shah](https://www.github.com/rhshah)
- [Ian Johnson](https://github.com/ionox0)
- [Shalabh Suman](https://github.com/shalabhsuman)