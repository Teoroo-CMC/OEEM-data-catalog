# O2EM-data-catalog

A curated catalog of publicly available datasets with properties relevant to organic electrochemical energy material (O2EM).

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

| Abbreviation/Symbol | Definition |
|:---|:---|
| MNHA | Maximum Number of Heavy Atoms |
| Exp | Experiments |
| MD | Molecular Simulation |
| DFT | Density Functional Theory |
| HOMO | Highest Occupied Molecular Orbital |
| LUMO | Lowest Unoccupied Molecular Orbital |
| EA | Electron Affinity |
| IP | Ionization Potential |
| AN | Acceptor Number |
| DN | Donor Number |
| DC | Dielectric Constant |
| MP | Melting Point |
| VISC | Viscosity |
| AqSol | Aqueous Solubility |
| SFE | Solvent Free Energy |
| μ | Molecular Dipole Moment |
| E₀ | Redox Potential |
| Eg | Band Gap |
| Tg | Glass Transition Temperature |

---

## 2.1 Organic Small Molecules

Small organic molecules with properties relevant to electrochemical systems, including redox activity and solvation behavior.

| Dataset | Elements | MNHA |  Method | Size | Key Properties | Access |
|:---------|:--------|:--|:------|:----|:----------|:--|
| QM9 |H,C,N,O,F| 9 |B3LYP/6-31G(2df,p) | 134K | HOMO, LUMO, μ| [Link](https://figshare.com/collections/Quantum_chemistry_structures_and_properties_of_134_kilo_molecules/978904) |
| QMugs |H,C,N,O,F,<br>P,S,Cl,Br,I| 100 |ωB97X-D/def2-SVP | ~2M | HOMO, LUMO, μ| [Link](https://libdrive.ethz.ch/index.php/s/X5vOBNSITAG5vzM) |
| JCESR |H,Li,Be,B,C,<br>N,O,F,Na,Mg,<br>Al,Si,P,S,Cl,<br>Ca,Zn,Br| 92 |B3LYP/6-31+G* | 25K | EA, IP | [Link](https://next-gen.materialsproject.org/jcesr) |
| MPcules |H,Li,B,C,N,O,<br>F,Mg,P,S,Cl| 31 |ωB97M-V/def2-TZVPPD | 577K | EA, IP, E₀| [Link](https://next-gen.materialsproject.org/molecules) |
| ConGen |H,B,C,N,O,F,<br>Si,P,S,Cl,Br| 92 |B3LYP/6-31+G* | 62K | EA, IP | [Link](https://github.com/jpmailoa/ConGen_Dataset/blob/main/Figure_3_Training_Data/data_Table_2/table_2_MP_IE_EA.csv) |
| OMEAD |H,Li,C,N,O,F,<br>Na,S,Cl,Zn,Se,Br| 122 |B3LYP/6–31G(d) | 26K | HOMO, LUMO, EA, IP, E₀ | [Link](https://github.com/rpcarvs/anima/blob/main/databases/OMEAD_26218.csv) |
| MNSOL |H,C,N,O,F,<br>Si,P,S,Cl,Br,I| 28 |Exp | 2K | SFE | [Link](https://conservancy.umn.edu/items/c3db00cf-d573-461b-adf5-389ff929d918) |
| ASMS |H,C,N,O,F,P,S,Cl,Br,I| 54 |Exp | ~2K | AqSol | [Link](https://pubs.acs.org/doi/suppl/10.1021/ci800406y/suppl_file/ci800406y_si_001.xls) |
| SOMAS |--| ? |PBE0/6–31 G** | 12K | HOMO, LUMO, AqSol | [Link](https://figshare.com/articles/dataset/SOMAS/14552697) |
| SCUT-DN |--| ? |Exp | 210 | DN | [Link](https://onlinelibrary.wiley.com/action/downloadSupplement?doi=10.1002%2Fanie.202411437&file=anie202411437-sup-0001-Supporting-Information-Sheets.xlsx) |
| Gutmann |--| ? |Exp | 224 | AN,DN | [Link](https://www.stenutz.eu/chem/gutmann.php) |
| SCUT-VISC |--| ? |MD | 277 | VISC | [Link](https://ars.els-cdn.com/content/image/1-s2.0-S2095495624007265-mmc2.xlsx) |
| Schrödinger-VISC |--| ? |Exp | 3K | VISC | [Link](https://static-content.springer.com/esm/art%3A10.1186%2Fs13321-024-00820-5/MediaObjects/13321_2024_820_MOESM2_ESM.csv) |
| 3DG-MP |--| ? |Exp | 237K | MP | [Link](https://github.com/Hyanqing/3DG-MP) |
| NanjingTech-DC |--| ? |Exp | 101 | DC | [Link](https://doi.org/10.60893/figshare.jcp.c.7791965) |

---

## 2.2 Molecular Crystals

Crystalline materials with properties relevant to ion transport and electrochemical systems.

| Dataset | Description | Method | Size | Key Properties | Access |
|:----------|:-------------|:------|:-----|:------------|:-----|
| OQMD |--| -- | -- | --- | [Link]() |
| ARVIS‐DFT |--| -- | -- | --- | [Link]() |

---

## 2.3 Electrolyte Mixtures

Liquid electrolyte systems including solvents, salts, and additives.

| Dataset | Description | Method | Size | Key Properties | Access |
|:----------|:-------------|:------|:-----|:------------|:-----|
| NUAA-COND |--| MD | 2K | Li diffusion coefficient, ionic conductivity | [Link](https://pubs.acs.org/doi/suppl/10.1021/acs.jpclett.5c02681/suppl_file/jz5c02681_si_002.csv) |
| ByteDance-COND |--| Exp | 10K | ionic conductivity | [Link](https://huggingface.co/ByteDance-Seed/bamboo_mixer) |
| CALiSol-23 |--| Exp | 13K | ionic conductivity | [Link](https://github.com/Pele0599/CALiSol-23) |

---

## 2.4 Polymers

Polymer systems with properties relevant to ion transport and electrochemical behavior.

| Dataset | Description | Method | Size | Key Properties | Access |
|:----------|:-------------|:------|:-----|:------------|:-----|
| PPPdb |--| Exp | 212 | Tg | [Link](https://pppdb.uchicago.edu/tg) |
| VitrimerVAE |--| MD | 8K | Tg | [Link](https://github.com/vashisth-lab/VitrimerVAE/tree/main) |
| PolyMetriX |--| Exp | 7K | Tg | [Link](https://zenodo.org/records/14980914) |
| Chemprop |--| xTB+B3LYP/DZP | 42K | EA, IP | [Link](https://github.com/coleygroup/polymer-chemprop-data) |
| OpenPoly |--| Exp | 13k | Tg, Eg, Tensile modulus | [Link](https://cleanenergymaterials.cn/polymer/polymer_database/experiment_polymer_database) |
| Polymer Scholar |--| Mixed | >100k | Tg, Eg, Tensile modulus, Young's modulus | [Link](https://polymerscholar.org/) |
| PoLyInfo |--| Exp | >200K | DC, Tg, Tensile modulus | [Link](https://polymer.nims.go.jp/) |
| PolyOmics |--| MD | 3M | DC, Tg, bulk modulus, self-diffusion coefficient | [Link](https://huggingface.co/datasets/yhayashi1986/PolyOmics) |
| PEDatamine |--| Exp | 5k | Tg, ionic conductivity | [Link](https://pedatamine.org/) |
| HTP-MD |--| MD | 6k | ionic conductivity, Li diffusion coefficient | [Link](https://www.htpmd.matr.io/ ) |
| Chem-Arr |--| Exp | 15k | ionic conductivity | [Link](https://github.com/learningmatter-mit/Chem-prop-pred) |

---
