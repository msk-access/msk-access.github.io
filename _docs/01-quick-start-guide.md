---
title: "Quick-Start Guide"
permalink: /docs/quick-start-guide/
excerpt: "How to quickly install and setup each worklfow for use on linux platform."
last_modified_at: 2018-05-11T15:12:19-04:00
redirect_from:
  - /theme-setup/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
---

[^structure]: See [**Structure** page]({{ "/docs/structure/" | relative_url }}) for a list of files and what they do.
[^anaconda]: See [**Anaconda** page]({{ "/docs/anaconda/" | relative_url }}) for installing miniconda and using bioconda for bioinformatics tools.
[^bioconda]: See [**Bioconda** page]({{ "/docs/bioconda/" | relative_url }}) for Using bioconda to install bioinformatics tools.


The MSK-ACCESS project is focused on incorporating methods of "collapsing" a bam file across reads that come from the same initial cfDNA molecule, as determined by Unique Molecular Indices included during library preparation.

We use Toil and CWL to combine various tools into a pipeline for collapsing UMI-tagged DNA molecules.

We draw on the work done by the Platform Informatics team at MSKCC in building Roslin and the IMPACT pipeline.


# Installing Workflows

### To view the content of the package

Go to MSK-ACCESS github page: <https://github.com/msk-access>

### Download

Please replace workflow with a given repository
```bash
curl -LO https://github.com/msk-access/workflow/archive/master.zip
```
