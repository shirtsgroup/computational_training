## Learning simulation tools
(Can be non-gromacs)
- [GROMACS Tutorials](http://www.mdtutorials.com/gmx/index.html) by Justin Lemkul
- [Bioinformatics With BB on YouTube](https://www.youtube.com/@jaannawaz2007)
- [Computational Chemistry Blog with numerous topics](https://www.compchems.com/) 
- Wei-Tse Hsu's [notes on advanced sampling](https://weitsehsu.com/course/advanced_sampling/) 
- LAMMPS
  - [LAMMPS documentation](https://docs.lammps.org/Manual.html) is pretty good, specifically the [“howto”s](https://docs.lammps.org/Howto.html#tutorials-howto) are useful
  - [LAMMPS tutorials](https://lammpstutorials.github.io/) by Simon Gravelle
- [LiveCoMS best practices articles](https://livecomsjournal.org/index.php/livecoms/catalog/category/bestpractices)
  - [Best practices for learning molecular simulation] (https://livecomsjournal.org/index.php/livecoms/article/view/v1i1e5957) 
- [Principles of modern molecular simulation methods](https://sites.engineering.ucsb.edu/~shell/che210d/assignments.html), lecture series by Scott Shell (UC Santa Barbara) 

## Analysis
 - [Calculating effective diffusion coefficients from bootstrapping](https://github.com/icomse/mcmd_summer_2022/blob/main/bootstrapping/README.md)
 - LiveCoMS article on ["Best practices in computing transport properties"](https://livecomsjournal.org/index.php/livecoms/article/view/v1i1e6324) 
 - [MDAnalysis](https://userguide.mdanalysis.org/stable/examples/README.html) has lots of common analysis tools.
 - [Practical PyMol for beginners](https://www.pymolwiki.org/index.php/Practical_Pymol_for_Beginners) provides an introduction on PyMol which allows individually coded analysis

## Building stuff
- The [RDKit Book](https://www.rdkit.org/docs/RDKit_Book.html) and [RDKit Cookbook](https://rdkit.org/docs/Cookbook.html): tools for cheminformatics, structure building, substructure search, etc.
- Open Force Field (OpenFF) resourcesP
  - [OpenFF cookbook](https://docs.openforcefield.org/projects/toolkit/en/stable/users/molecule_cookbook.html): examples of how to set up systems 
  - [OpenFF Interchange](https://docs.openforcefield.org/projects/interchange/en/stable/using/intro.html): for exporting your OpenFF systems to GROMACS, OpenMM, LAMMPS, etc
- Polymerist [toolkit](https://github.com/timbernat/polymerist) and [examples](https://github.com/timbernat/polymerist_examples): Tim Bernat (Shirts Group) tools for end-to-end MD system building, parameterization, and MD file setup for any linear multimeric organic polymer-like system (synthetic polymers, proteins, lipids, etc.)

## Parameterizing Stuff
- [EspalomaCharge GitHub](https://github.com/choderalab/espaloma_charge) : easy-to-install GNN charge model for very quick partial charge assignment
  - Also the [accompanying paper](https://arxiv.org/abs/2302.06758) for those interested in the nuts and bolts
