### Absorption <a id="model-parameters-and-assumptions-absorption"></a>

The measured solubility of Warfarin was taken from Product information from [Drugbank](#main-references) (see [Section 2.2.1](#invitro-and-physico-chemical-data)).

Tablet dissolution was modeled using an empirical Weibull dissolution approach. Both enantiomers share the same absorption processes.

### Distribution <a id="model-parameters-and-assumptions-distribution"></a>

After testing the organ-plasma partition coefficient and cell permeability calculation methods available in PK-Sim®, observed clinical data were best described by choosing the partition coefficient calculation method by `Rodgers and Rowland` and cellular permeability calculation method by `Charged dependent Schmitt`.

### Metabolism and Elimination <a id="model-parameters-and-assumptions-metabolism-and-elimination"></a>

Clearance of warfarin was described through enzymatic and reductive pathways, with only a negligible contribution from renal excretion of unchanged parent drug. The stereospecific nature of warfarin metabolism was explicitly represented by modeling the two enantiomers separately, with different sets of enzymes responsible for their elimination.

For **S-warfarin**, metabolism is dominated by CYP2C9, which is the principal enzyme responsible for oxidative clearance. 
A smaller contribution from CYP3A4 was also included, together accounting for the observed in-vivo clearance. 
In addition, a reductive pathway leading to alcohol metabolites was implemented, using literature-based plasma clearance values and a blood-to-plasma ratio of 0.55 ([Bi 2018](#main-references), [Dickinson 2007](#main-references), [Sawada 1985](#main-references), [Essential Health](#main-references)), leading to a hepatic `Specific Clearance` of 0.02 1/min. 
The renal elimination of unchanged S-warfarin was parameterized but remains negligible, consistent with clinical evidence of ~ 1% fraction excreted in urine [FDA 2010](#main-references). 
Kinetic constants for CYP2C9 and CYP3A4 were taken from in-vitro studies and the associated `Kcat` were optimized within the current model to achieve agreement with observed plasma concentrations. These optimized values reflect the dominant role of CYP2C9 and the minor but non-negligible contribution of CYP3A4 to the overall clearance of the S-enantiomer.

The clearance of **R-warfarin** was represented by three oxidative enzymes—CYP1A2, CYP2C19, and CYP3A4—together with the same reductive alcohol pathway and minor renal clearance. 
Experimental information on kinetic constants for R-warfarin is less abundant, and therefore the Km and Vmax values were adopted from a previously developed PBPK model in PK-Sim. The values for the Michaelis–Menten constants are relatively high (Km values of 648 µM for CYP1A2, 391 µM for CYP2C19, and 586 µM for CYP3A4), which indicates a low affinity of these enzymes for R-warfarin. The reduction to alcohols and renal clearance contribute only marginally to the overall disposition of the R-enantiomer.

### Automated Parameter Identification <a id="model-parameters-and-assumptions-parameter-identification"></a>

This is the result of the final parameter identification.

| Model Parameter      | Optimized Value | Unit |
| -------------------- | --------------- | ---- |
| `Intestinal permeability (transcellular)` |0.0015|cm/min|
| `S-Warfarin CYP2C9 kcat` |0.2|1/min|
| `S-warfarin CYP3A4 kcat` |0.09|1/min|


