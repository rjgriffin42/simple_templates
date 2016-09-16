# Simple Templates

This repository contains a few example templates to use with [scriptorium](https://github.com/jasedit/scriptorium), which provides a system by which LaTeX templates can be integrated in a MultiMarkdown workflow for writing academic papers more easily.

# Installation

Clone this repository into the templates directory of scriptorium:

```
cd papers_base/templates/
git clone https://github.com/jasedit/simple_templates.git
```

# Usage

In the metadata header of a paper created using the `new_paper.sh` command in papers_base, the last two lines of the metadata should look akin to:

```
latex input: report/setup.tex
latex footer: report/footer.tex
```

Where `report` in both lines is the template in use.
