# pdbsum-binder
Analysis of PDBsum-related data via active Jupyter sessions provided via MyBinder.org. Adapt the demonstrations to analyze your favorite structures.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/pdbsum-binder/main?filepath=index.ipynb)


*tl;dr:*  
Click any `launch binder` badge on this page to use the demonstrations inside your browser.

------


***pdbsum-binder:  Jupyter notebook environment for analysis of PDBsum-related data.***

A launchable, working Jupyter-based environment that has a collection of demonstrations of analysis of PDBsum-related data served via MyBinder.org.

You can also easily adapt the demonstrations to analyze your favorite structures.

Meant to be self-contained and ready-to-go. No installations or copying of notebooks is necessary if `launch binder` is clicked. Everything will just work. Of course, static versions of the notebooks can also be used. I recommend rendering the static versions by placing the URLs into the [nbviewer](https://nbviewer.jupyter.org/). The views provided by [nbviewer](https://nbviewer.jupyter.org/) look best and Github's rendering often times out (your mileage may vary).

[PDBsum](http://www.ebi.ac.uk/thornton-srv/databases/cgi-bin/pdbsum/GetPage.pl?pdbcode=index.html) itself is accessible online [here](http://www.ebi.ac.uk/thornton-srv/databases/cgi-bin/pdbsum/GetPage.pl?pdbcode=index.html).

Usage
-----

This repository is set up to allow analysis of [PDBsum](http://www.ebi.ac.uk/thornton-srv/databases/cgi-bin/pdbsum/GetPage.pl?pdbcode=index.html)-related data after pressing the `launch binder` button above or below. The target use case is where you want to be thorough in your analyses with the add of compuatation or analyze multiple structures. You shouldn't need to install anything.

In the notebooks that can be launched, I have added some examples illustrating how to get data and process ir easily with Python and convert to other forms. Alternatively, the notebooks with most of resources can be viewed statically and [nbviewer](https://nbviewer.jupyter.org/) is recommended for that as discussed above.

## Attributions

Users of [PDBsum](http://www.ebi.ac.uk/thornton-srv/databases/cgi-bin/pdbsum/GetPage.pl?pdbcode=index.html)-sourced data should probably cite:

- [Laskowski RA, Jabłońska J, Pravda L, Vařeková RS, Thornton JM. 2018. PDBsum: Structural summaries of PDB entries. Protein Sci. 27(1):129-134. doi: 10.1002/pro.3289. Epub 2017 Oct 27. PMID: 28875543](https://pubmed.ncbi.nlm.nih.gov/28875543/)

***Clarifying Software Attribution: I, Wayne, am not involved with PDBsum in any way. The Thorton Research Group at EBI are the developers and maintainers of PDBsum,  see [their materials](https://www.ebi.ac.uk/research/thornton). I simply set up this repository to make analysis of the data easier without installation headaches.***

The [PDBsum](http://www.ebi.ac.uk/thornton-srv/databases/cgi-bin/pdbsum/GetPage.pl?pdbcode=index.html) author/develops contact information is [here](http://www.ebi.ac.uk/thornton-srv/databases/cgi-bin/pdbsum/GetPage.pl?doc=TRUE&template=contactus.html&pdbcode=n/a).

I, Wayne, did share Jupyter/Python-based utilities for use with the data available from PDBsum; these are available [here](https://github.com/fomightez/structurework/tree/master/pdbsum-utilities) and utilized in the notebooks in this repository to process data and allow easily converting the results to other forms.



## Related

- My [pdbsum-utilities sub-repo](https://github.com/fomightez/structurework/tree/master/pdbsum-utilities)

- See [here](https://github.com/fomightez/structurework#related-binderized-utilities) for a listing of resources in a similar vein yet targeted to macromolecular structure data. In particular, see [cl_demo-binder](https://github.com/fomightez/cl_demo-binder) for the companion set to this one.

- The path to getting the interaction details between two chains from PDBsum data shown in the notebooks here gets used in the pipeline for the notebook [Report if residues interacting with a specific chain have equivalent residues in an hhsuite-generated alignment](https://nbviewer.jupyter.org/github/fomightez/hhsuite3-binder/blob/main/notebooks/Report%20if%20residues%20interacting%20with%20a%20specific%20chain%20have%20equivalent%20residues%20in%20an%20hhsuite-generated%20alignment.ipynb) that can be run in launches from the [hhsuite3-binder](https://github.com/fomightez/hhsuite3-binder). There is a version built on that which uses snakemake to process several combinations of structures and chains all once and make a report for each desired pair that also relies on this path.

## Technical notes

This repository is set up to make use of the binder service offered by [MyBinder.org](https://mybinder.org/). See their site for more information about Binder.

I borrrowed the 'warning' highlight/introductory text about notebooks at the top of the included notebook from Tim Sherratt's notebook [here](https://github.com/GLAM-Workbench/te-papa-api/blob/master/Exploring-the-Te-Papa-collection-API.ipynb).

Click `launch binder` below to start using the demonstrations.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/pdbsum-binder/main?filepath=index.ipynb)
