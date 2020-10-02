---
authors:
- admin
categories: []
date: "2020-10-02T00:00:00Z"
draft: false
featured: false
image:
  caption: ""
  focal_point: ""
lastMod: "2020-10-02T00:00:00Z"
projects: []
subtitle: Hours away from some of the most amazing places on earth
summary: Jena offers easy access to a huge range of history and outdoors opportunities
tags: []
title: The Heart of Europe!
---

```python
from IPython.core.display import Image
Image('https://www.python.org/static/community_logos/python-logo-master-v3-TM-flattened.png')
```




![png](./index_1_0.png)




```python
print("Welcome to Academic!")
```

    Welcome to Academic!


## Install Python and JupyterLab

[Install Anaconda](https://www.anaconda.com/distribution/#download-section) which includes Python 3 and JupyterLab.

Alternatively, install JupyterLab with `pip3 install jupyterlab`.

## Create or upload a Jupyter notebook

Run the following commands in your Terminal, substituting `<MY-WEBSITE-FOLDER>` and `<SHORT-POST-TITLE>` with the file path to your Academic website folder and a short title for your blog post (use hyphens instead of spaces), respectively:

```bash
mkdir -p <MY-WEBSITE-FOLDER>/content/post/<SHORT-POST-TITLE>/
cd <MY-WEBSITE-FOLDER>/content/post/<SHORT-POST-TITLE>/
jupyter lab index.ipynb
```

The `jupyter` command above will launch the JupyterLab editor, allowing us to add Academic metadata and write the content.


