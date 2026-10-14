---
# New code entry: `hugo new content code/<repo-name>` creates this page.
# Add a featured.jpg (card image) to the new folder, fill in the fields below,
# and link the paper by adding `projects: [<repo-name>]` and `url_code:` to its
# page in content/publication/.
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
summary: One-line description of what the code does. Python · License
date: {{ .Date }} # set to the date the code was first released (cards are ordered by it)
show_date: false

tags: []

url_code: https://github.com/d3lab-iisc/{{ .File.ContentBaseName }}
links:
  - name: Paper
    url: https://doi.org/
  # - name: Zenodo # software archive, if any
  #   url: https://doi.org/10.5281/zenodo.XXXXXXX

image:
  caption: ''
  focal_point: Smart
---

Short overview of the method and what the repository contains.

### Quick start

```bash
git clone https://github.com/d3lab-iisc/{{ .File.ContentBaseName }}.git
```

### Citation

If you use this code, please cite the paper:

> Authors. Title. *Journal*, volume, article (year). [doi:](https://doi.org/)
