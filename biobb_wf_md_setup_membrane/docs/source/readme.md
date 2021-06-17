[![](https://readthedocs.org/projects/biobb-wf-md-setup-membrane/badge/?version=latest)](https://biobb-wf-md-setup-membrane.readthedocs.io/en/latest/)

# Using prepared systems from MemProtMD (http://memprotmd.bioch.ox.ac.uk/)

**MemProtMD is a database of around 3500 intrinsic membrane protein structures identified in the Protein Data Bank, inserted into simulated lipid bilayers using Coarse-Grained Self Assembly Molecular Dynamics simulations.**

*Newport, Thomas D. et al. The MemProtMD database: a resource for membrane-embedded protein structures and their lipid interactions. Nucleic Acids Research, Volume 47, Issue D1, 08 January 2019, Pages D390–D397, https://doi.org/10.1093/nar/gky1047*

***

## Settings

### Biobb modules used

* [biobb_io](https://github.com/bioexcel/biobb_io): Tools to fetch biomolecular data from public databases.
* [biobb_md](https://github.com/bioexcel/biobb_md): Tools to setup and run Molecular Dynamics simulations.
* [biobb_analysis](https://github.com/bioexcel/biobb_analysis): Tools to analyse Molecular Dynamics trajectories.

### Auxiliar libraries used

* [nb_conda_kernels](https://github.com/Anaconda-Platform/nb_conda_kernels): Enables a Jupyter Notebook or JupyterLab application in one conda environment to access kernels for Python, R, and other languages found in other environments.
* [nglview](http://nglviewer.org/#nglview): Jupyter/IPython widget to interactively view molecular structures and trajectories in notebooks.
* [ipywidgets](https://github.com/jupyter-widgets/ipywidgets): Interactive HTML widgets for Jupyter notebooks and the IPython kernel.
* [os](https://docs.python.org/3/library/os.html): Python miscellaneous operating system interfaces
* [plotly](https://plot.ly/python/offline/): Python interactive graphing library integrated in Jupyter notebooks.
* [simpletraj](https://github.com/arose/simpletraj): Lightweight coordinate-only trajectory reader based on code from GROMACS, MDAnalysis and VMD.

### Conda Installation

```console
git clone https://github.com/bioexcel/biobb_wf_md_setup_membrane.git
cd biobb_wf_md_setup_membrane
conda env create -f conda_env/environment.yml
conda activate biobb_MDsetup_Membrane_tutorial
jupyter-nbextension enable --py --user widgetsnbextension
jupyter-nbextension enable --py --user nglview
jupyter-notebook biobb_wf_md_setup_membrane/notebooks/Membrane-Protein-MD-Setup.ipynb
```

***

## Tutorials

Click here to [view tutorials in Read the Docs](https://biobb-wf-md-setup-membrane.readthedocs.io/en/latest/)

***

## Version
2021.2 Release

## Copyright & Licensing
This software has been developed in the [MMB group](http://mmb.irbbarcelona.org) at the [BSC](http://www.bsc.es/) & [IRB](https://www.irbbarcelona.org/) for the [European BioExcel](http://bioexcel.eu/), funded by the European Commission (EU H2020 [823830](http://cordis.europa.eu/projects/823830), EU H2020 [675728](http://cordis.europa.eu/projects/675728)).

* (c) 2015-2021 [Barcelona Supercomputing Center](https://www.bsc.es/)
* (c) 2015-2021 [Institute for Research in Biomedicine](https://www.irbbarcelona.org/)

Licensed under the
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0), see the file LICENSE for details.

![](https://bioexcel.eu/wp-content/uploads/2019/04/Bioexcell_logo_1080px_transp.png "Bioexcel")
