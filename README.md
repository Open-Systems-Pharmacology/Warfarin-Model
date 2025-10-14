# Warfarin-Model
Whole-body PBPK model of Warfarin. 

## Repository files
This repository contains:

- a PK-Sim snapshot (*.json) file of the current whole-body PBPK model of warfarin
- static content (e.g. text blocks, *.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation-plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model
  
The model was developed and evaluated for S-Warfarin and R-Warfarin using data from several clinical studies. 
For S-Warfarin, the model was developed and evaluated against IV administration (0.375 mg/kg) and oral administration (dosing range of Warfarin 7.5 mg to 30 mg in the fasted state (equivalent to 3.75 mg to 15 mg of S-Warfarin), and 25-26 mg (equivalent to 12.5-13 mg of S-Warfarin) in the fed state). 
For R-Warfarin, the model was developed and evaluated against oral administration (dosing range of Warfarin 25 mg in the fasted state (equivalent to 12.5 mg of R-Warfarin)). 

The PK-Sim snapshot file contains simulations and the observed data of all clinical studies used for model development and evaluation. 

<b>Caveat: No experimental values were found for R-Warfarin metabolism, therefore, values were kept from the previous PK-Sim project </b><br>

## Code of conduct

Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution

We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).
