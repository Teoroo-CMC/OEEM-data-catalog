# OEEM-data-catalog

A curated catalog of publicly available datasets with properties relevant to Organic Electrochemical Energy Material (OEEM). 

If you find it useulf, please refer to our original publication: Z.-Y. Zhang, G. Savvas, J. Li, et al. “ AI-Accelerated Design and Modeling of Organic Electrochemical Energy Materials: From Redox-Active Molecules to Polymer Electrolytes.” Macromolecular Materials and Engineering 311, no. 9 (2026): e70340, [https://doi.org/10.1002/mame.70340](https://doi.org/10.1002/mame.70340).

---

# 📌 1. Scope

This repository indexes publicly available datasets relevant to:

- Molecular and polymer property prediction
- Electrolyte modeling and design, including liquid and polymer electrolytes
- Redox-active molecules, organic electrodes, and battery-relevant organic materials
- Molecular crystals and solid-state organic materials relevant to electrochemical systems

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
| BP | Boiling Point |
| VISC | Viscosity |
| COND | Ionic Conductivity |
| AqSol | Aqueous Solubility |
| SFE | Solvent Free Energy |
| μ | Molecular Dipole Moment |
| E₀ | Redox Potential |
| Eg | Band Gap |
| Tg | Glass Transition Temperature |

---

## 2.1 Organic Small Molecules

Small organic molecules with properties relevant to electrochemical systems, including redox activity, solvation behavior, and thermodynamic properties.

| Dataset | Elements | MNHA |  Method | Size | Key Properties | Access |
|:------------|:---|:-|:---------|:-|:----------|:-|
| QM9 |H,C,N,O,F| 9 |B3LYP/6-31G(2df,p) | 134K | HOMO, LUMO, μ| [Link](https://figshare.com/collections/Quantum_chemistry_structures_and_properties_of_134_kilo_molecules/978904) |
| QMugs |H,C,N,O,F,P,<br>S,Cl,Br,I| 100 |ωB97X-D/def2-SVP | ~2M | HOMO, LUMO, μ| [Link](https://libdrive.ethz.ch/index.php/s/X5vOBNSITAG5vzM) |
| JCESR |H,Li,Be,B,C,<br>N,O,F,Na,Mg,<br>Al,Si,P,S,Cl,<br>Ca,Zn,Br| 92 |B3LYP/6-31+G(d) | 25K | EA, IP | [Link](https://next-gen.materialsproject.org/jcesr) |
| MPcules |H,Li,B,C,N,O,<br>F,Mg,P,S,Cl| 31 |ωB97M-V/def2-TZVPPD | 577K | EA, IP, E₀| [Link](https://next-gen.materialsproject.org/molecules) |
| ConGen |H,B,C,N,O,F,<br>Si,P,S,Cl,Br| 92 |B3LYP/6-31+G(d) | 62K | EA, IP | [Link](https://github.com/jpmailoa/ConGen_Dataset/blob/main/Figure_3_Training_Data/data_Table_2/table_2_MP_IE_EA.csv) |
| OMEAD |H,Li,C,N,O,<br>F,Na,S,Cl,Zn,<br>Se,Br| 122 |B3LYP/6–311G(d,p) | 26K | HOMO, LUMO, EA, IP, E₀ | [Link](https://github.com/rpcarvs/anima/blob/main/databases/OMEAD_26218.csv) |
| MNSOL |H,C,N,O,F,Si,<br>P,S,Cl,Br,I| 28 |Exp | 2K | SFE | [Link](https://conservancy.umn.edu/items/c3db00cf-d573-461b-adf5-389ff929d918) |
| ASMS |H,C,N,O,F,<br>P,S,Cl,Br,I| 54 |Exp | ~2K | AqSol | [Link](https://pubs.acs.org/doi/suppl/10.1021/ci800406y/suppl_file/ci800406y_si_001.xls) |
| SOMAS |H,B,C,N,O,<br>F,Si,P,S,Cl,<br>Ge,As,Se,Br,I| 66 |PBE0/6-31G(d,p) | 12K | HOMO, LUMO, AqSol | [Link](https://figshare.com/articles/dataset/SOMAS/14552697) |
| SCUT-DN |H,C,N,O,F,P,<br>S,Cl,Se,Br,I| 26 |Exp | 210 | DN | [Link](https://onlinelibrary.wiley.com/action/downloadSupplement?doi=10.1002%2Fanie.202411437&file=anie202411437-sup-0001-Supporting-Information-Sheets.xlsx) |
| Gutmann |H,C,N,O,F,P,<br>S,Cl,Cr,Br,I| 26 |Exp | 224 | AN, DN | [Link](https://www.stenutz.eu/chem/gutmann.php) |
| SCUT-VISC |H,C,O,F| 14 |MD | 277 | VISC | [Link](https://ars.els-cdn.com/content/image/1-s2.0-S2095495624007265-mmc2.xlsx) |
| Schrödinger-VISC |H,C,N,O,F,Si,<br>P,S,Cl,Br,I| 36 |Exp | 3K | VISC | [Link](https://static-content.springer.com/esm/art%3A10.1186%2Fs13321-024-00820-5/MediaObjects/13321_2024_820_MOESM2_ESM.csv) |
| 3DG-MP |H,C,N,O,F,P,<br>S,Cl,Se,Br,I| 123 |Exp | 237K | MP | [Link](https://github.com/Hyanqing/3DG-MP) |
| OPERA |H,B,C,N,O,<br>F,Si,P,S,<br>Cl,Se,Br,I| 131 |Exp | 15K | MP, BP | [Link](https://github.com/kmansouri/OPERA/blob/master/OPERA_Data.zip) |
| NanjingTech-DC |H,C,N,O,F,<br>P,S| 13 | Exp | 101 | DC | [Link](https://doi.org/10.60893/figshare.jcp.c.7791965) |
| CIAC-RP |H,C,N,O,S,Cl| 47 | ωB97XD/6-31+(d,p)/SMD | 1K | Reduction potential | [Link](https://zenodo.org/records/10828373) |
| OMol25 | 83 elements | 350 | ωB97M-V/def2-TZVPD | 83M | HOMO, LUMO  | [Link](https://www.materialsdatafacility.org/spotlight/omol25) |
| Batt-P30K | H,C,N,O,F,<br>P,S,Cl | 16 | ωB97X-V/def2-TZVPPD/SMD | 30K | HOMO, LUMO, Eg, μ, EA, IP | [Link](https://github.com/Teoroo-CMC/Batt-SLM) |

---

## 2.2 Molecular Crystals

Organic crystalline materials with properties relevant to ion transport and electrochemical systems.

| Dataset | Elements | Method | Size | Key Properties | Access |
|:------------|:------|:---------|:-|:----------|:-|
| OMDB-GAP1 |65 elements| PBE | 12K | Eg | [Link](https://omdb.mathub.io/dataset) |
| OMC25 | H,B,C,N,O,F,Si,P,S,Cl,Br,I | PBE+D3 | ~230K | Total energy, Stress | [Link](https://huggingface.co/datasets/facebook/OMC25) |
| JARVIS-DFT |Almost full periodic table| PBE+OptB88vdW | 37K | Eg | [Link](https://jarvis-materials-design.github.io/dbdocs/jarvisdft/) |
| MolCryst |H, C, N, and O | PBE-D4 | AIMD trajectories (25-500K) | Total energy and forces | [Link](https://github.com/adamlaho/MolCryst) |

---

## 2.3 Electrolyte Mixtures

Liquid electrolyte systems including solvents, salts, and additives.

| Dataset | Elements | Method | Size | Key Properties | Access |
|:------------|:------|:---------|:-|:----------|:-|
| NUAA-COND |H,Li,C,N,<br>O,F,P,S| MD | 2K | Li diffusion coefficient, COND | [Link](https://pubs.acs.org/doi/10.1021/acs.jpclett.5c02681#_i2) |
| Bamboo |H,Li,B,C,N,<br>O,F,P,S,Cl| Exp | 10K | COND | [Link](https://github.com/ByteDance-Seed/bamboo_mixer/blob/main/data_oss/formula_finetune_exp_data.json.xz) |
| CALiSol-23 |H,Li,B,C,N,<br>O,F,P,S,Cl| Exp | 13K | COND | [Link](https://github.com/Pele0599/CALiSol-23) |
| DiffMix |H,Li,C,N,O,<br>F,P,S| Exp | 25K | COND, Excess_molar_enthalpy, Excess_molar_volume | [Link](https://github.com/BattModels/DiffMix-NatCommData/tree/main/training_data) |
| Electrolytomics |H,Li,B,C,N,<br>O,F,P,S,Cl,As| Exp | >10K | COND, Oxidative stability, Coulombic efficiency  | [Link](https://github.com/AmanchukwuLab/electrolytomics/tree/main/datasets/raw) |
| LIBE |H,Li,C,N,O,<br>F,P,S| ωB97X-V/def2-TZVPPD/SMD | 17K | Enthalpy, Entropy, Gibbs free energy | [Link](https://figshare.com/articles/dataset/Lithium-Ion_Battery_Electrolyte_LIBE_dataset/14226464?file=28071129) |
| MolSet |H,Li,B,C,N,<br>O,F,P,S,Cl| Exp | 11K | COND | [Link](https://github.com/Xiangwen-Wang/FragForm/blob/main/dataset/molset.csv) |
| ELLIE |H,Li,C,N,O,<br>F,Na,P,S| Exp | 106 | COND | [Link](https://pubs.acs.org/aelccp/article-supplement/5207270/xlsx/nz-2026-01023w_si_002/) |

---

## 2.4 Polymers

Polymer systems with properties relevant to ion transport and electrochemical behavior.

| Dataset | Elements | Method | Size | Key Properties | Access |
|:------------|:------|:---------|:-|:----------|:-|
| Polymer Genome |--| Exp/Computed | >30K | EA, IP, Eg, Tg, Tensile strength, Young's modulus | [Link](https://www.polymergenome.org/) |
| PPPdb |--| Exp | 212 | Tg | [Link](https://pppdb.uchicago.edu/tg) |
| VitrimerVAE |H,C,N,O| MD | 8K | Tg | [Link](https://github.com/vashisth-lab/VitrimerVAE/blob/main/Calibration/tg_vitrimer_calibrated.csv) |
| NeurIPS-OPP2025 |---| MD | 1500 | Tg | [Link](https://www.kaggle.com/competitions/neurips-open-polymer-prediction-2025/data) |
| PolyMetriX |H,Li,B,C,N,<br>O,F,Na,Si,P,<br>S,Cl,K,Ca,Zn,<br>Ge,Se,Br,Cd,<br>Sn,I,Te,Pb| Exp | 7K | Tg | [Link](https://zenodo.org/records/14980914) |
| Vipea |H,B,C,N,O,<br>F,S,Cl,Br,I| xTB+B3LYP/DZP | 42K | EA, IP | [Link](https://github.com/coleygroup/polymer-chemprop-data/blob/main/datasets/vipea/) |
| OpenPoly |H,Li,B,C,N,<br>O,F,Na,Si,P,<br>S,Cl,K,Ca,Fe,<br>Zn,Ge,Se,Br,Cd,<br>Sn,I,Te,Pb| Exp | 13k | Eg, Tg, Tensile strength | [Link](https://cleanenergymaterials.cn/polymer/polymer_database/experiment_polymer_database) |
| Polymer Scholar |--| Mixed | >100k | Eg, Tg, Tensile strength, Young's modulus | [Link](https://polymerscholar.org/) |
| PoLyInfo |--| Exp | >200K | DC, Tg, Tensile modulus | [Link](https://polymer.nims.go.jp/) |
| PolyOmics |--| MD | 3M | DC, Tg, bulk modulus, self-diffusion coefficient | [Link](https://huggingface.co/datasets/yhayashi1986/PolyOmics) |
| PolymerElectrolyte |H,C,N,O,<br>Si,P,S| Exp | 655 | Tg, COND | [Link](https://github.com/nschauser/PolymerElectrolyte/blob/main/_Cleaned_Final_Data_6_2_2020.csv) |
| HTP-MD |H,C,N,O,F,<br>Si,P,S,Cl,| MD | 6k | COND, Li diffusion coefficient | [Link](https://www.htpmd.matr.io/ ) |
| ChemPropPred |H,B,C,N,O,<br>F,Al,Si,P,<br>S,Cl,Ca,| Exp | 10k | COND | [Link](https://github.com/learningmatter-mit/Chem-prop-pred/blob/main/data/clean_train_data.csv) |
| OPoly26 | H,Li,B,C,N,<br>O,F,Na,Mg,Al,<br>P,S,Cl,K,Ca,<br>Fe,Co,Ni,Cu,<br>Zn,Br,Sr,I,<br>Cs,La| ωB97M-V/def2-TZVPD | >6M <br> (Substructures) | HOMO, LUMO | [Link](https://huggingface.co/datasets/colabfit/OPoly26-train) |

---
