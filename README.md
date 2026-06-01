# Battery-Relevant Dataset Catalog

A curated catalog of publicly available molecular and materials datasets with properties relevant to electrochemical and battery systems, including organic small molecules, molecular crystals, electrolyte mixtures, and polymers.

---

# 📌 1. Scope

This repository indexes publicly available datasets relevant to:

- Molecular and polymer property prediction
- Electrolyte systems modeling and design
- Battery materials discovery and simulation
- Solid-state and crystalline materials modeling

It does NOT host datasets, only provides structured references to original sources.

---

# 📚 2. Dataset Categories

Datasets are organized by **material type**, reflecting chemical and physical modeling workflows.

---

## 2.1 Organic Small Molecules

Small organic molecules with properties relevant to electrochemical systems, including redox activity and solvation behavior.

| Dataset | Method | Size | Key Properties | Access |
|:--------|:--------|:------|:----------------|:------|
| QM9 | B3LYP/6-31G(2df,p) | 134K | HOMO/LUMO, dipole moment| [Link](https://quantum-machine.org/datasets/) |
| QMugs | ωB97X-D/def2-SVP | 2M | HOMO/LUMO, dipole moment, atomic partial charges| [Link](https://libdrive.ethz.ch/index.php/s/X5vOBNSITAG5vzM) |
| JCESR | B3LYP/6-31+G* | 25K | EA/IP | [Link](https://next-gen.materialsproject.org/jcesr) |
| MPcules | ωB97M-V/def2-TZVPPD | 577K | EA/IP, redox potential| [Link](https://next-gen.materialsproject.org/molecules) |
| ConGen | B3LYP/6-31+G* | 62K | EA/IP | [Link](https://github.com/jpmailoa/ConGen_Dataset) |
| Gutmann | Experiments | 224 | acceptor number, donor number | [Link](https://www.stenutz.eu/chem/gutmann.php) |
| MNSOL | Experiments | 2K | solvent free energy | [Link](https://conservancy.umn.edu/items/c3db00cf-d573-461b-adf5-389ff929d918) |
| -- | Experiments | > 4K | temperature-dependent viscosity | [Link](https://link.springer.com/article/10.1186/s13321-024-00820-5) |
| 3DG-MP | Experiments | 237K | melting point | [Link](https://github.com/Hyanqing/3DG-MP) |
| -- | Experiments | 101 | dielectric constant | [Link](https://doi.org/10.60893/figshare.jcp.c.7791965) |
| QCML | PBE0 | 33.5M | dipole moment, atomic partial charges | [Link](https://zenodo.org/records/14859804) |
| OMol25 | ωB97M-V/def2-TZVPD | 83M | EA/IP, spin gap | [Link](https://huggingface.co/facebook/OMol25) |

---

## 2.2 Molecular Crystals

Crystalline materials with properties relevant to ion transport and electrochemical systems.

| Dataset | Method | Size | Key Properties | Access |
|:--------|:--------|:------|:----------------|:------|
| OQMD | -- | -- | --- | [Link](#) |
| ARVIS‐DFT | -- | -- | --- | [Link](#) |

---

## 2.3 Electrolyte Mixtures

Liquid electrolyte systems including solvents, salts, and additives.

| Dataset | Method | Size | Key Properties | Access |
|:--------|:--------|:------|:----------------|:------|
| CALiSol-23 | experiments | 13K | conductivity | [Link](https://github.com/Pele0599/CALiSol-23) |
| -- | MD + experiments | 13K | conductivity | [Link](https://www.nature.com/articles/s42256-025-01173-w) |

---

## 2.4 Polymers

Polymer systems with properties relevant to ion transport and electrochemical behavior.

| Dataset | Method | Size | Key Properties | Access |
|:--------|:--------|:------|:----------------|:------|
| Chemprop | B3LYP/DZP | 42K | EA/IP | [Link](https://github.com/coleygroup/polymer-chemprop-data) |
| PoLyInfo | Experiments | >200K | glass transition temperature, modulus | [Link](https://polymer.nims.go.jp/) |
| PEDatamine | Experiments | 5k | glass transition temperature, ionic conductivity | [Link](https://pedatamine.org/) |
| HTP-MD | MD | 6k | ionic conductivity, Li Diffusivity | [Link](https://www.htpmd.matr.io/ ) |
| Chem-Arr | Experiments | 15k | ionic conductivity | [Link](https://github.com/learningmatter-mit/Chem-prop-pred) |
| OpenPoly | Experiments | 13k | glass transition temperature, bandgap, modulus | [Link](https://cleanenergymaterials.cn/polymer/polymer_database/experiment_polymer_database) |

---
