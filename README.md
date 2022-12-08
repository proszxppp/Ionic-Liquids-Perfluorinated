# Ionic-Liquids

The current repository contains the full RESP charge files of cations and anions forming ILs considered in the recent ILs paper on perfluorinated anionic species. 

The ESP analysis presented validates the charge generation by comparing the molecular ESP scanned at different ab initio levels. The traditional HF/6-31G* scan in vacuo generates high-quality atomic charges that reproduce satisfactorily the ESP data scanned at other higher-level selections, including B3LYP, BP86, M06-2X, MN15, PBE, PW6B96 and many others, all of which are combined with larger basis sets (def2-TZVPP and def2-QZVPP) and are performed in vacuo or IEFPCM implicit solvent. 

As the ESP analysis is only based on static structures without dynamic rearrangments, we also generate RESP charges with higher-level data (the large def2-QZVPP basis set) and simulate the system, the reuslts of which are compared with the simulation outcome with the HF/6-31G*-targeted charges, in order to provide a face-to-face comparison and validation. 

The current folder contains all these higher-level-targeted atomic charges for interested readers to probe the details of the QM-level scan in charge generation. 
