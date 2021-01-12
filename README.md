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

PDBsum itself is accessible online [here](http://www.ebi.ac.uk/thornton-srv/databases/cgi-bin/pdbsum/GetPage.pl?pdbcode=index.html).

Usage
-----

This repository is set up to allow analysis of PDVsum-related data after pressing the `launch binder` button above or below. The target use case is where you want to be thorough in your analyses with the add of compuatation or analyze multiple structures. You shouldn't need to install anything.

In the notebooks that can be launched, I have added some examples illustrating how to get data and process ir easily with Python and convert to other forms. Alternatively, the notebooks with most of resources can be viewed statically and [nbviewer](https://nbviewer.jupyter.org/) is recommended for that as discussed above.

## Attributions

Users of PDBsum-sourced data should probably cite:

- [Laskowski RA, Jabłońska J, Pravda L, Vařeková RS, Thornton JM. 2018. PDBsum: Structural summaries of PDB entries. Protein Sci. 27(1):129-134. doi: 10.1002/pro.3289. Epub 2017 Oct 27. PMID: 28875543](https://pubmed.ncbi.nlm.nih.gov/28875543/)

***Clarifying Software Attribution: I, Wayne, am not involved with PDBsum in any way. Roman Laskowski. See their materials. I simply set up this repository to make analysis of the data easier without installation headaches.***

The PDBsum author/develops contact information is [here](http://www.ebi.ac.uk/thornton-srv/databases/cgi-bin/pdbsum/GetPage.pl?doc=TRUE&template=contactus.html&pdbcode=n/a).

I, Wayne, did share Jupyter/Python-based utilities for use with the data available from PDBsum; these are available [here](https://github.com/fomightez/structurework/tree/master/pdbsum_utilities) and utilized in the notebooks in this repository to process data and allow easily converting the results to other forms.


## Related

- My [pdbsum_utilities sub-repo](https://github.com/fomightez/structurework/tree/master/pdbsum_utilities)

- See [here](https://github.com/fomightez/structurework#related-binderized-utilities) for a listing of resources in a similar vein yet targeted to macromolecular structure data. In particular, see [cl_demo-binder](https://github.com/fomightez/cl_demo-binder) for the companion set to this one.

## Technical notes

This repository is set up to make use of the binder service offered by [MyBinder.org](https://mybinder.org/). See their site for more information about Binder.


Click `launch binder` below to start using the demonstrations.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/pdbsum-binder/main?filepath=index.ipynb)
