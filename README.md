Contributors: 2021 N. Artrith (nartrith@atomistic.net), T. Morawietz, H. Guo, and A. Urban 

# List of Public Tools and Data for Atomistic Machine Learning

**A Collection of Public Open-Source Tools and Databases for Atomistic Machine Learning**

## Table of Contents

* [Contributing](#contributing)
* [ML atomistic potentials](#ml-atomistic-potentials)
  * [ANN based potential implementations](#ann-based-potential-implementations)
  * [Other ML based potential implementations](#other-ml-based-potential-implementations)
* [ML tools and packages for materials science and drug discovery applications](#ml-tools-and-packages-for-materials-science-and-drug-discovery-applications)
* [Databases](#databases)
  * [General databases](#general-databases)
  * [Databases for inorganic materials](#databases-for-inorganic-materials)
  * [Databases for organic molecules and materials](#databases-for-organic-molecules-and-materials)
* [Workflow management](#workflow-management)
* [Peer-reviewed articles referring to this document](#peer-reviewed-articles-referring-to-this-document)

## Contributing

We welcome everybody to contribute to this list.  Your name will be added to the list of contributors at the top of this document.

## ML atomistic potentials

### ANN based potential implementations

Entries sorted by the year of the publication.

| Name                                                                   | Features                                                                    | Reference                                                                                                    |
| ---------------------------------------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| [ænet](http://ann.atomistic.net)                                       | Capable of handling many chemical species | [Artrith, Urban, *Comput. Mater. Sci.* **114** (2016) 135](https://doi.org/10.1016/j.commatsci.2015.11.047)  |
| [Amp](https://bitbucket.org/andrewpeterson/amp)                        | Large descriptor library                                                    | [Khorshidi, Peterson, *Comput. Phys. Commun.* **207** (2016) 310](https://doi.org/10.1016/j.cpc.2016.05.010) |
| [ANI](https://github.com/isayev/ASE_ANI)                               | Accurate potential for molecular systems                                    | [Smith, Isayev, Roitberg, *Chem. Sci.* **8** (2017) 3192](https://doi.org/10.1039/C6SC05720A)                |
| [TensorMol](https://github.com/jparkhill/TensorMol)                    | Electrostatics and van der Waals interactions                               | [Yao et al., *Chem. Sci.* **9** (2018) 2261](https://doi.org/10.1039/C7SC04934J)                             |
| [DeePMD-kit](https://github.com/deepmodeling/deepmd-kit)               | GPU support                                            | [Wang et al., *Comput. Phys. Commun.* **228** (2018) 178](https://doi.org/10.1016/j.cpc.2018.03.016)         |
| [SchNetPack](https://github.com/atomistic-machine-learning/schnetpack) | Feature learning                                                            | [Schütt et al., *J. Chem. Theory Comput.* **15** (2019) 448](https://doi.org/10.1021/acs.jctc.8b00908)       |
| [N2P2](https://compphysvienna.github.io/n2p2)                          | Behler-Parinello neural network potential                                   | [Singraber et al., *J. Chem. Theory Comput.* **15** (2019) 1827](https://doi.org/10.1021/acs.jctc.8b00770)   |
| [SchNarc](https://github.com/schnarc/SchNarc) | Extension to multiple electronic states based on [SchNet](https://github.com/atomistic-machine-learning/schnetpack) and [SHARC](https://sharc-md.org/)                                                            | [Westermayr et al., *J. Phys. Chem. Lett.* **11** (2020) 3828](https://doi.org/10.1021/acs.jpclett.0c00527)       |
| [PANNA](https://gitlab.com/PANNAdevs/panna)                | Properties from neural network architectures        | [Lot et al., *Comput. Phys. Commun.* **256**, (2020) 107402](https://doi.org/10.1016/j.cpc.2020.107402)                                            |
| [TorchANI](https://github.com/aiqm/torchani)                               | Pytorch implementation of ANI                                    | [Gao et al., *J. Chem. Inf. Model.*, 10.1021/acs.jcim.0c00451 (2020)](https://doi.org/10.1021/acs.jcim.0c00451)                |

### Other ML based potential implementations

| Name                                          | Description            | Reference                                                                                                                                                                                   |
| --------------------------------------------- | ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [GAP/SOAP](http://libatoms.org/Home/Software) | GPR based ML potential | [Bartók et al., *Phys. Rev. Lett.* **104** (2010) 136403](https://doi.org/10.1103/PhysRevLett.104.136403) [*Phys. Rev. B* **87** (2013) 184115](https://doi.org/10.1103/PhysRevB.87.184115) |
| [SNAP](https://github.com/FitSNAP) | Linear ML potential based on bispectrum components of the local neighbor density | [Thompson et al., *J. Comput. Phys.* **285** (2015) 316](https://doi.org/10.1016/j.jcp.2014.12.018) |
| [AutoForce](https://github.com/amirhajibabaei/AutoForce) | SGPR based ML potential (on-the-fly) | [Hajibabaei et al., *Phys. Rev. B.* **103** (2021) 214102](https://doi.org/10.1103/PhysRevB.103.214102) |

## ML tools and packages for materials science and drug discovery applications

| Name                                                       | Description                                         | Reference                                                                                                                                         |
| ---------------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| [COMBO](https://github.com/tsudalab/combo)                 | Bayesian Optimization Library                       | [Ueno et al., *Materials Discovery* **4** (2016) 18](https://doi.org/10.1016/j.md.2016.04.001)                                                   |
| [Magpie](https://bitbucket.org/wolverton/magpie)           | ML framework                                  | [Ward, Wolverton et al., *npj Computational Materials.* **2** (2016) 16028](https://doi.org/10.1038/npjcompumats.2016.28)                         |
| [PROPhet](https://biklooost.github.io/PROPhet)             | Neural networks to materials predictions            | [Kolb et al., *Sci Rep* **7** (2017) 1192](https://www.nature.com/articles/s41598-017-01251-z)                                                   |
| [SISSO](https://github.com/rouyang2017/SISSO)              | ML framework                                  | [Ouyang, Ghiringhelli et al., *Phys. Rev. Mater.* **2**, (2018) 083802](https://doi.org/10.1103/PhysRevMaterials.2.083802)                         |
| [MatMiner](https://hackingmaterials.github.io/matminer)    | Feature construction library                        | [Ward, Jian et al., *Comput. Mater. Sci.* **152**  (2018) 60](https://doi.org/10.1016/j.commatsci.2018.05.018)                                    |
| [AFLOW-ML](http://aflowlib.org/aflow-ml)                   | ML framework                                  | [Gossett, Curtarolo et al., *Comput. Mater. Sci.* **152** (2018) 134](https://doi.org/10.1016/j.commatsci.2018.03.075)                           |
| [Phoenics](https://github.com/aspuru-guzik-group/phoenics) | Bayesian Optimization and kernel density estimation | [Häse et al., *ACS Cent. Sci.* **4** (2018) 1134](https://pubs.acs.org/doi/abs/10.1021/acscentsci.8b00307)                                        |
| [JARVIS-ML](https://ctcms.nist.gov/jarvisml)               | Properties predictions                              | [Choudhary et al., *Phys. Rev. Materials* **2** (2018) 083801](https://doi.org/10.1103/PhysRevMaterials.2.083801)                                |
| [OMDB-ML](https://omdb.mathub.io/ml)                       | Properties predictions                              | [Olsthoorn et al., *Adv. Quantum Technol.* **2** (2019) 1900023](https://doi.org/10.1002/qute.201900023)                                          |
| [DeepChem](https://deepchem.io)                             | Democratizing Deep-Learning for Drug Discovery       | [Ramsundar et al., *O'Reilly Media* (2019)](https://www.oreilly.com/library/view/deep-learning-for/9781492039822)                             |
| [ShiftML](http://shiftml.org)                             | ML framework for predicting chemical shifts in molecular solids       | [Paruzzo et al., *Nat. Commun.* **9** (2019) 4501](https://doi.org/10.1038/s41467-018-06972-x)                             |
| [MaterialNet](https://github.com/ToyotaResearchInstitute/materialnet) | A web-based graph explorer for materials science data    | [Choudhury et al., *JOSS* **5**, (2020) 2105](https://doi.org/10.21105/joss.02105)

## Databases

### General databases

| Name                                                       | Description                                         | Reference                                                                                                                                         |
| ---------------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| [NOMAD Repository](https://nomad-repository.eu)           | Open-Access Platform for Data Sharing  | [Draxl, Scheffler, *J. Phys. Mater.* **2** (2019) 036001](https://doi.org/10.1088/2515-7639/ab13bb)  |
| [Materials Cloud](http://www.materialscloud.org)          | Platform for Open Computational Science  | [Talirz et al., arXiv:2003.12510 (2020)](https://arxiv.org/abs/2003.12510)  |

### Databases for inorganic materials

| Name                                                       | Description                                         | Reference                                                                                                                                         |
| ---------------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| [American Mineralogist Crystal Structure Database](http://rruff.geo.arizona.edu/AMS/amcsd.php) |Crystal structure database for mineralogist | [Downs and Hall-Wallace, *American Mineralogist* **88** (2003) 247](https://www.geo.arizona.edu/xtal/group/pdf/am88_247.pdf) |
| [COD](http://www.crystallography.net/cod/search.html) | Crystallography Open Database | [Grazulis et al. (2009)](http://scripts.iucr.org/cgi-bin/paper?S0021889809016690),  [Gražulis (2012)](https://doi.org/10.1093/nar/gkr900), [Gražulis (2015)](http://scripts.iucr.org/cgi-bin/paper?S1600576714025904), [Merkys (2016)](http://scripts.iucr.org/cgi-bin/paper?S1600576715022396), [Quirós (2018)](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-018-0279-6), [Vaitkus (2021)](https://scripts.iucr.org/cgi-bin/paper?S1600576720016532)|
| [AFLOW](http://www.aflowlib.org)                          | Ab initio computational materials science database  | [Curtarolo et al., *Cumput. Mater. Sci.* **58** (2012) 218](https://doi.org/10.1016/j.commatsci.2012.02.005) |
| [NREL MatDB](https://materials.nrel.gov)                  | Computational materials database with focus on renewable energy applications | [Stevanovic et al. (2012)](http://dx.doi.org/10.1103/PhysRevB.85.115104), [Lany (2013)](http://dx.doi.org/10.1103/PhysRevB.87.085112), [Lany (2015)](http://dx.doi.org/10.1088/0953-8984/27/28/283203)  |
| [Materials Project](https://materialsproject.org)         |  A materials genome approach to accelerating materials innovation | [Jain et al., *APL Materials* **1** (2013) 011002](https://doi.org/10.1063/1.4812323)
| [OQMD](http://oqmd.org)                                   | Database of DFT calculated thermodynamic and structural materials properties | [Kirklin et al., *Npj Comput. Mater.* **1** (2015) 15010](http://dx.doi.org/10.1038/npjcompumats.2015.10) |
| [COMBO](https://github.com/tsudalab/combo)                 | Bayesian Optimization Library                       | [Ueno et al., *Materials Discovery* **4** (2016) 18](https://doi.org/10.1016/j.md.2016.04.001)                                                   |
| [Open Catalyst Project](https://github.com/Open-Catalyst-Project/ocp/blob/master/DATASET.md)                 | Using AI to model and discover new catalysts to address the energy challenges posed by climate change                           | [Facebook AI and Carnegie Mellon (2020)](https://opencatalystproject.org)                                                   |
| [JARVIS-API](https://jarvis.nist.gov)                     | Integrated Infrastructure for Data-driven Materials Design | [Choudhary et al., arXiv:2007.01831 (2020)](https://arxiv.org/abs/2007.01831) |

### Databases for organic molecules and materials

| Name                                                       | Description                                         | Reference                                                                                                                                         |
| ---------------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| [MoleculeNet](http://moleculenet.ai)                       | Large scale benchmark for molecular machine learning | [Wu et al., *Chem. Sci.*  **9**  (2018) 513](https://doi.org/10.1039/C7SC02664A)                                                                |
| [FMODB](https://drugdesign.riken.jp/FMODB/)                | Database of quantum mechanical FMO calculations                  | [Kato et al., *J. Chem. Inf. Model.* 10.1021/acs.jcim.0c00273 (2020)](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00273)                                                               |
| [QM-sym](https://github.com/XI-Lab/QM-sym-database)                | Symmetrized quantum chemistry database of 135k organic molecules  | [Liang et al., *Sci. Data* **6** (2020) 213](https://doi.org/10.1038/s41597-019-0237-9)                                                               |

## Workflow management

| Name                                                       | Description                                         | Reference                                                                                                                                         |
| ---------------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Research Object Crate](https://www.researchobject.org/) | A JSON-based approach for research object serialization | [Bechhofer et al., *Future Generation Computer Systems* **29** (2013) 599-611](https://doi.org/10.1016/j.future.2011.08.004) |
| [Common Workflow Language](https://www.commonwl.org/) | An open standard for analysis workflows and tools | [Amstutz et al., *Common Workflow Language, v1.0* (2016)](https://doi.org/10.6084/m9.figshare.3115156.v2) |
| [DLHub](https://www.dlhub.org/) | Sharing of ML models and workflows | [Chard et al., *IEEE IPDPS* (2019) 283-292](https://arxiv.org/pdf/1811.11213), [Blaiszik et al., *MRS Commun.* **9** (2019) 1125–1133](https://doi.org/10.1557/mrc.2019.118) |


## Peer-reviewed articles referring to this document

1. H. Guo,  Q. Wang,  A Stuke,  A. Urban, and  N. Artrith, *Front. Energy Res.* just accepted, **(2021)** **Open Access**.</li>
2. A. M. Miksch, T. Morawietz, J. Kästner, A. Urban, and N. Artrith,
   *Machine Learning: Science and Technology*, in press, **(2021)** **Open Access** DOI: https://doi.org/10.1088/2632-2153/abfd96 . </li>
3. T. Morawietz and N. Artrith, 
   *J. Comput. Aided Mol. Des.* **35**, 557-586 (2021) **Open Access** DOI: https://doi.org/10.1007/s10822-020-00346-6 . </li>

