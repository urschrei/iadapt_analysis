# iAdapt Survey Analysis
## Author
<div itemscope itemtype="https://schema.org/Person"><a itemprop="sameAs" content="https://orcid.org/0000-0003-4379-2450" href="https://orcid.org/0000-0003-4379-2450" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon">Stephan Hügel</a></div>

## DOI
[![DOI](https://zenodo.org/badge/662217973.svg)](https://zenodo.org/badge/latestdoi/662217973)

## Introduction
This [notebook](iadapt_geoforum.ipynb) contains the data analysis of pre- and post survey results relating to phase I of the iAdapt project. The notebook is also available as a [PDF](iadapt_geoforum.pdf)

In step 1, Likert data from the results are first converted to ordinal values, then analysed using the Mann-Whitney U test. Statistically significant question results have a Cohen's d effect assigned.

In step 2, pre- and post question data are graphed in small multiples according to their capability grouping, for further discussion.

### QA and Data Integrity
Start time and response ID are not used in this analysis but are retained for data quality and assurance reasons, allowing them to be matched with the retained read-only survey response data if necessary.

# Installation
If you wish to reproduce this analysis, install the requisite python packages from [requirements.txt](requirements.txt), then open the [notebook](iadapt_geoforum.ipynb) using Jupyter.

# Software used in this analysis

Caswell, T. A., Lee, A., Andrade, E. S. de, Droettboom, M., Hoffmann, T., Klymak, J., Hunter, J., Firing, E., Stansby, D., Varoquaux, N., Nielsen, J. H., Root, B., May, R., Gustafsson, O., Elson, P., Seppänen, J. K., Lee, J.-J., Dale, D., hannah, … Moad, C. (2023). matplotlib/matplotlib: REL: v3.7.1. Zenodo. https://doi.org/10.5281/zenodo.7697899

Granger, B. E., & Pérez, F. (2021). Jupyter: Thinking and Storytelling With Code and Data. Computing in Science & Engineering, 23(2), 7–14. https://doi.org/10.1109/MCSE.2021.3059263

Harris, C. R., Millman, K. J., Walt, S. J. van der, Gommers, R., Virtanen, P., Cournapeau, D., Wieser, E., Taylor, J., Berg, S., Smith, N. J., Kern, R., Picus, M., Hoyer, S., Kerkwijk, M. H. van, Brett, M., Haldane, A., Río, J. F. del, Wiebe, M., Peterson, P., … Oliphant, T. E. (2020). Array programming with NumPy. Nature, 585(7825), 357–362. https://doi.org/10.1038/s41586-020-2649-2

Hunter, J. D. (2007). Matplotlib: A 2D graphics environment. Computing in Science & Engineering, 9(3), 90–95. https://doi.org/10.1109/MCSE.2007.55

McKinney, W. (2010). Data Structures for Statistical Computing in Python. In S. van der Walt & J. Millman (Eds.), Proceedings of the 9th Python in Science Conference (pp. 56–61). https://doi.org/10.25080/Majora-92bf1922-00a

Seabold, S., & Perktold, J. (2010). statsmodels: Econometric and statistical modeling with python. 9th Python in Science Conference.

The pandas development team. (2023). pandas-dev/pandas: Pandas. Zenodo. https://doi.org/10.5281/zenodo.8092754
