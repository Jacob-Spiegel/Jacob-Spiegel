---
permalink: /Programs/
title: "Programs"
toc: true
toc_sticky: true
toc_label: "Programs"
---

## Computer Aided Drug Design (CAAD) Programs

- **AutoGrow4**: AutoGrow4 is an open-source program for semi-automated computer-aided drug discovery. It uses a genetic algorithm to evolve predicted ligands on demand and so is not limited to a virtual library of pre-enumerated compounds. AutoGrow4 is a useful tool for generating entirely novel drug-like molecules and for optimizing preexisting ligands.<br />
    &nbsp;&nbsp;&nbsp;&nbsp;Documentation, Forum, & Download: <https://durrantlab.pitt.edu/autogrow4/> <br />
    &nbsp;&nbsp;&nbsp;&nbsp;Git Repository: <https://git.durrantlab.pitt.edu/jdurrant/autogrow4.git><br />

## Cheminformatic Programs

- **Gypsum-DL**: Gypsum-DL is a free, open-source program that converts 1D and 2D small-molecule representations (SMILES strings or flat SDF files) into 3D models. It outputs models with alternate ionization, tautomeric, chiral, cis/trans isomeric, and ring-conformational states.<br />
    &nbsp;&nbsp;&nbsp;&nbsp;Documentation, Forum, & Download: <https://durrantlab.pitt.edu/gypsum-dl/><br />
    &nbsp;&nbsp;&nbsp;&nbsp;Git Repository: <https://git.durrantlab.pitt.edu/jdurrant/gypsum_dl.git>

- **SMILESMerge**: SMILESMerge is a free, open-source program that merges two SMILES strings to produce a novel child compound. SMILESMerge uses the AutoGrow4 crossover algorithm to create *de novo* compounds and was inspired by the program LigMerge. SMILESMerge also provides the option to automate 1/2D SMILES to 3D conversion using Gypsum-DL as well as ADME-PK filters using GlauconiteFilter.<br />
    &nbsp;&nbsp;&nbsp;&nbsp;Git Repository: <https://github.com/Jacob-Spiegel/SMILESMerge.git>

- **SMILESClickChem**: SMILESClickChem is a free, open-source program that creates novel compounds by performing *in silico* reactions. SMILESClickChem uses the AutoGrow4 mutation algorithm to create *de novo* compounds and was inspired by the program AutoClickChem. SMILESClickChem provides a predefined library of 94 high-yielding chemical reactions, however, its intuitive plugin-style architecture allows for the easy expansion of reaction sets and libraries of reactants. SMILESClickChem also provides the option to automate 1/2D SMILES to 3D conversion using Gypsum-DL as well as ADME-PK filters using GlauconiteFilter.<br />
    &nbsp;&nbsp;&nbsp;&nbsp;Git Repository: <https://github.com/Jacob-Spiegel/SMILESClickChem.git>

- **GlauconiteFilter**: GlauconiteFilter is a free, open-source program for parallelized ADME-PK chemical filtration. GlauconiteFilter uses the AutoGrow4 filtration algorithm to SMILES strings. It is a highly parallelized algorithm that has been test on both SMP and MPI high performance computing environments. GlauconiteFilter provides nine predefined chemical filters, however, its intuitive plugin-style architecture allows for the easy expansion of filter options. GlauconiteFilter also provides the option to automate 1/2D SMILES to 3D conversion using Gypsum-DL.<br />
    &nbsp;&nbsp;&nbsp;&nbsp;Git Repository: PENDING
