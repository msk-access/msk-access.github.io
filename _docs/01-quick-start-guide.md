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

# Installing Workflows

### To view the content of the package

Go to MSK-ACCESS github page: <https://github.com/msk-access>

### Download

Please replace workflow with a given repository
```bash
curl -LO https://github.com/msk-access/workflow/archive/master.zip
```

### Install

Install these tools **with sudo** rights:

```bash
unzip master.zip
cd PIe-master
python setup.py install
```

Install these tools **without sudo** rights:

```bash
unzip master.zip
cd workflow-master
python setup.py install --user
```

### Quick Access

Add following to your **.bashrc** or **.bash_profile** for accessing the `*.cwl` tools:

When installed **without sudo** rights:

```bash
# Set PATH to include local python bin if found
if [ -d "$HOME/.local/bin" ]; then
    PATH="$HOME/.local/bin:$PATH"
fi
```