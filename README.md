# Vulnerability analysis of container images


[![DOI](https://zenodo.org/badge/307525894.svg)](https://zenodo.org/badge/latestdoi/307525894)


The paper is written in Latex and can be compiled as follows:
```
pdflatex paper ; bibtex paper ; pdflatex paper ; pdflatex paper
```

Data stored in `Data` was generated using the Anchore, Clair and Vuls 
container image scanners. 

The notebook in `analysis.ipynb` describes our data analysis and 
generates the figures of the paper.

The scripts in `Scripts` were used to update and minify container images.
