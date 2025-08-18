### Absorption <a id="model-parameters-and-assumptions-absorption"></a>

The measured solubility of Warfarin was taken from Product information from X (see [Section 2.2.1](#invitro-and-physico-chemical-data)).

Tablet dissolution was modeled using an empirical Weibull dissolution approach.

### Distribution <a id="model-parameters-and-assumptions-distribution"></a>

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim®, observed clinical data was best described by choosing the partition coefficient calculation by `Schmitt` and cellular permeability calculation by `Charged dependent Schmitt`.

### Metabolism and Elimination <a id="model-parameters-and-assumptions-metabolism-and-elimination"></a>


### Automated Parameter Identification <a id="model-parameters-and-assumptions-parameter-identification"></a>

This is the result of the final parameter identification.

| Model Parameter      | Optimized Value | Unit |
| -------------------- | --------------- | ---- |
| `S-Warfarin CYP2C9 kcat` |          0.2       |   1/min   |
| `S-warfarin CYP3A4 kcat` |        0.09         |  1/min    |


