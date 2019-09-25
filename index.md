---
layout: splash
classes:
  - landing
  - dark-theme
excerpt: "Precision Informatics engine (PIe) help documents"
last_modified_at: 2018-05-11T15:12:19-04:00
tags: [python, cwl, json, toil]
header:
  image: /assets/images/background.jpg
  caption: "Photo credit: [**Canva**](https://www.canva.com/)"
toc: true
---
# Welcome to MSK-ACCESS help documents

[PIe](https://github.com/NorthwellHealth-HumanGenomics/PIe) came into existence because of the need to write flexible, portable and easy to use tools.

## MSK-ACCESS workflows features

1. **Containers** : Using docker to host tool images to be used by Common Workflow Language
2. **Common Workflow Language (CWL)** : Have commandline tools written in common workflow language specification.
3. **Workflow of workflow** : We will join multiple CWL workflows togather to create a final workflow.

- - - -

### Installing package

Here is how to install these tools without sudo rights:

Please replace _workflow_ with repo containing the workflow of your interest

```bash
curl -LO https://github.com/msk-access/workflow/archive/master.zip
unzip workflow-master.zip
cd workflow-master
python setup.py install --user
```

Add this to your `~/.bash_profile` to get access to the `*.cwl` tools:

```bash
# Set PATH to include local python bin if found
if [ -d "$HOME/.local/bin" ]; then
    PATH="$HOME/.local/bin:$PATH"
fi
```