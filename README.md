# ATM-ATR-DDR-DrugRepositioning-Model
A mechanistic computational model of the DNA damage response in ATM/ATR-deficient conditions (e.g., Ataxia-Telangiectasia), integrating p53 signaling and drug repositioning strategies for Omaveloxolone and Spermidine.
Overview

This repository provides a mechanistic computational model simulating the DNA damage response (DDR) under conditions of ATM/ATR deficiency, such as Ataxia-Telangiectasia. The model integrates multiple regulatory modules—including ATM/ATR–p53 signaling, NRF2/KEAP1 antioxidant response, and spermidine-induced autophagy—to explore cell fate decisions and predict the potential effects of repurposed drugs (Omaveloxolone and Spermidine).

The model is implemented in COPASI and available in SBML format.

Key Features

Integrated DDR Pathway: Simulates interconnected pathways involving DNA damage production/repair, ATM/ATR and p53 signaling, NRF2 antioxidant defense, and autophagy.
ATM/ATR Deficiency: Models cellular phenotypes characteristic of Ataxia-Telangiectasia and related disorders.
Drug Repositioning: Predicts the impact of Omaveloxolone (NRF2 activator) and Spermidine (autophagy inducer and ATR modulator).
Cell Fate Decisions: Quantifies outcomes such as apoptosis, senescence, and survival via downstream effectors (p21, BAX, PUMA).
Open Model: Provided in COPASI/SBML format for reproducibility and further development.
Getting Started

Requirements
COPASI (for simulation and visualization)
Alternatively, any SBML-compatible simulation tool
Usage
Download or clone this repository:
git clone https://github.com/YOUR-USERNAME/ATM-ATR-DDR-DrugRepositioning-Model.git
Open AT_ATM_ATR_forDR_v1.xml in COPASI or your preferred SBML tool.
Run time-course simulations, modify kinetic parameters, or explore drug effects by adjusting Omaveloxolone and Spermidine concentrations.
Model Structure

DNA Damage Production & Repair: Basal DNA damage, ATM/ATR-mediated repair, NRF2-driven antioxidant repair, autophagy-mediated (saturable) repair.
ATM/ATR–p53 Module: Damage sensing and p53 activation, including regulation by HDAC4, TOPBP1, and CK2.
NRF2/KEAP1 Module: Drug-modulated antioxidant response and DNA repair enhancement.
Autophagy Module: Spermidine-induced autophagy and positive modulation of ATR signaling.
Cell Fate Outcomes: p53-driven induction of p21, BAX, PUMA determining arrest, apoptosis, or survival.
For a comprehensive description, see the model notes in the SBML file.


Contact

For questions, suggestions, or contributions, contact:

Francesco Pappalardo, University of Catania (francesco.pappalardo@unict.it)
Giulia Russo, University of Catania (giulia.russo@unict.it)
