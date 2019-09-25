---
title: "Organization of the package"
permalink: /docs/structure/
excerpt: "Structure of the package."
last_modified_at: 2018-05-11T15:12:19-04:00
redirect_from:
  - /theme-setup/
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
---

### Tree for the current organization of the package

```bash

├── CHANGES.md
├── LICENSE
├── README.md
├── \*.cwl
├── docs
│   
├── workflow
│   ├── __init__.py
│   ├── _version.py
│   ├── data
│   └── util.py
└── setup.py
```

### Overview of directories

- tests: contains wrapper scripts written in python for testing workflows
- \*.cwl: contains cwl scripts in YAML format.
- docs: contains documentation and web-hosting using Gitbook
