# List of public tools and data for atomistic machine learning

A collection of tools and databases for atomistic machine learning

## ML atomistic potentials

### ANN based potential implementations

| Name                                                                   | Features                                                                    | Reference                                                                                                    |
| ---------------------------------------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| [ænet](http://ann.atomistic.net)                                       | Accurate and efficient potential: Capable of handling many chemical species | [Artrith, Urban, *Comput. Mater. Sci.* **114** (2016) 135](https://doi.org/10.1016/j.commatsci.2015.11.047)  |
| [Amp](https://bitbucket.org/andrewpeterson/amp)                        | Large descriptor library                                                    | [Khorshidi, Peterson, *Comput. Phys. Commun.* **207** (2016) 310](https://doi.org/10.1016/j.cpc.2016.05.010) |
| [ANI](https://github.com/isayev/ASE_ANI)                               | Accurate potential for molecular systems                                    | [Smith, Isayev, Roitberg, *Chem. Sci.* **8** (2017) 3192](https://doi.org/10.1039/C6SC05720A)                |
| [TensorMol](https://github.com/jparkhill/TensorMol)                    | Electrostatics and van der Waals interactions                               | [Yao et al., *Chem. Sci.* **9** (2018) 2261](https://doi.org/10.1039/C7SC04934J)                             |
| [DeePMD-kit](https://github.com/deepmodeling/deepmd-kit)               | GPU support and feature learning                                            | [Wang et al., *Comput. Phys. Commun.* **228** (2018) 178](https://doi.org/10.1016/j.cpc.2018.03.016)         |
| [SchNetPack](https://github.com/atomistic-machine-learning/schnetpack) | Feature learning                                                            | [Schütt et al., *J. Chem. Theory Comput.* **15** (2019) 448](https://doi.org/10.1021/acs.jctc.8b00908)       |
| [SchNarc](https://github.com/schnarc/SchNarc) | Extension to multiple electronic states based on [SchNet](https://github.com/atomistic-machine-learning/schnetpack) and [SHARC](https://sharc-md.org/)                                                            | [Westermayr et al., *J. Phys. Chem. Lett.* **11** (2020) 3828](https://doi.org/10.1021/acs.jpclett.0c00527)       |
| [N2P2](https://compphysvienna.github.io/n2p2)                          | Behler-Parinello neural network potential                                   | [Singraber et al., *J. Chem. Theory Comput.* **15** (2019) 1827](https://doi.org/10.1021/acs.jctc.8b00770)   |

### Other ML based potential implementations

| Name                                          | Description            | Reference                                                                                                                                                                                   |
| --------------------------------------------- | ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [GAP/SOAP](http://libatoms.org/Home/Software) | GPR based ML potential | [Bartók et al., *Phys. Rev. Lett.* **104** (2010) 136403](https://doi.org/10.1103/PhysRevLett.104.136403) [*Phys. Rev. B* **87** (2013) 184115](https://doi.org/10.1103/PhysRevB.87.184115) |
| [SNAP](https://github.com/FitSNAP) | Linear ML potential based on bispectrum components of the local neighbor density | [Thompson et al., *J. Comput. Phys.* **285** (2015) 316](https://doi.org/10.1016/j.jcp.2014.12.018) |

## ML packages for materials science applications

| Name                                                       | Description                                         | Reference                                                                                                                                         |
| ---------------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| [COMBO](https://github.com/tsudalab/combo)                 | Bayesian Optimization Library                       | [Ueno et. al., *Materials Discovery* **4** (2016) 18] (https://doi.org/10.1016/j.md.2016.04.001)                                                   |
| [Magpie](https://bitbucket.org/wolverton/magpie)           | General purpose ML                                  | [Ward, Wolverton et. al., *npj Computational Materials.* **2** (2016) 16028](https://doi.org/10.1038/npjcompumats.2016.28)                         |
| [PROPhet](https://biklooost.github.io/PROPhet)             | Neural networks to materials predictions            | [Kolb et. al., *Sci Rep* **7** (2017) 1192] (https://www.nature.com/articles/s41598-017-01251-z)                                                   |
| [SISSO](https://github.com/rouyang2017/SISSO)              | General purpose ML                                  | [Ouyang, Ghiringhelli et al., *Phys. Rev. Mater.* **2**, (2018) 083802](https://doi.org/10.1103/PhysRevMaterials.2.083802)                         |
| [MatMiner](https://hackingmaterials.github.io/matminer)    | Feature construction library                        | [Ward, Jian et. al., *Comput. Mater. Sci.* **152**  (2018) 60](https://doi.org/10.1016/j.commatsci.2018.05.018)                                    |
| [AFLOW-ML](http://aflowlib.org/aflow-ml)                   | General purpose ML                                  | [Gossett, Curtarolo et. al., *Comput. Mater. Sci.* **152** (2018) 134] (https://doi.org/10.1016/j.commatsci.2018.03.075)                           |
| [Phoenics](https://github.com/aspuru-guzik-group/phoenics) | Bayesian Optimization and kernel density estimation | [Häse et. al., *ACS Cent. Sci.* **4** (2018) 1134](https://pubs.acs.org/doi/abs/10.1021/acscentsci.8b00307)                                        |
| [JARVIS-ML](https://ctcms.nist.gov/jarvisml)               | Properties predictions                              | [Choudhary et. al., *Phys. Rev. Materials* **2** (2018) 083801] (https://doi.org/10.1103/PhysRevMaterials.2.083801)                                |
| [OMDB-ML](https://omdb.mathub.io/ml)                       | Properties predictions                              | [Olsthoorn et. al., *Adv. Quantum Technol.* **2** (2019) 1900023](https://doi.org/10.1002/qute.201900023)                                          |
| [PANNA](https://gitlab.com/PANNAdevs/panna)                | Properties from neural network architectures        | [Lot et al., *Comput. Phys. Commun.* **256**, (2020) 107402](https://doi.org/10.1016/j.cpc.2020.107402)                                            |
| [MaterialNet](https://github.com/ToyotaResearchInstitute/materialnet) | A web-based graph explorer for materials science data    | [Choudhury et al., *JOSS* **5**, (2020) 2105](https://doi.org/10.21105/joss.02105)                                                 |

## ML packages for drug discovery applications

| Name | Description                                         | Reference |
| ---------------------------------------------------------- | --------------------------------------------------- | --------- |
| [DeepChem](https://deepchem.io)                             | Democratizing Deep-Learning for Drug Discovery       | [Ramsundar,  et al., *O'Reilly Media* (2019) ] (https://www.oreilly.com/library/view/deep-learning-for/9781492039822)                             |

## Databases

### General databases

| Name                                                       | Description                                         | Reference                                                                                                                                         |
| ---------------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Materials Cloud] (http://www.materialscloud.org)          |   |   |
| [NOMAD Repository] (https://nomad-repository.eu)           |   |   |

### Databases for inorganic materials

| Name                                                       | Description                                         | Reference                                                                                                                                         |
| ---------------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| [COMBO](https://github.com/tsudalab/combo)                 | Bayesian Optimization Library                       | [Ueno et. al., *Materials Discovery* **4** (2016) 18] (https://doi.org/10.1016/j.md.2016.04.001)                                                   |
| [Materials Project] (https://materialsproject.org)         |                                                     |       |
| [AFLOW] (http://www.aflowlib.org)                          |   |   |
| [OQMD] (http://oqmd.org)                                   |   |   |
| [JARVIS-API] (https://jarvis.nist.gov)                     |   |   |
| [NREL MatDB] (https://materials.nrel.gov)                  |   |   |
| [Materials Cloud] (http://www.materialscloud.org)          |   |   |
| [NOMAD Repository] (https://nomad-repository.eu)           |   |   |

### Databases for organic molecules and materials

| Name                                                       | Description                                         | Reference                                                                                                                                         |
| ---------------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| [MoleculeNet](http://moleculenet.ai)                       | Large scale benchmark for molecular machine learning | [Wu,  et al., *Chem. Sci.*  **9**  (2018) 513] (https://doi.org/10.1039/C7SC02664A)                                                                |
| [FMODB](https://drugdesign.riken.jp/FMODB/)                | Quantum mechanical FMO calculations                  | [Kato, et al., *J. Chem. Inf. Model.* (2020)] (https://doi/10.1021/acs.jcim.0c00273)                                                               |
