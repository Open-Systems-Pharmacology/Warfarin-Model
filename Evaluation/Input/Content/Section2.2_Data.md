### In vitro / physico-chemical Data <a id="invitro-and-physico-chemical-data"></a>

A literature search was performed to collect available information on physicochemical properties of Warfarin. The obtained information from literature is summarized in the table below. 

**Physicochemical and binding properties**

| **Parameter** | **Unit** | **Value** | **Source** | **Description** |
|:--------------|:---------|----------:|:-----------|:----------------|
| MW            | g/mol    | 308.33    | 	[Drugbank](#main-references)          | Molecular weight |
| pK<sub>a</sub> | –        | 5.00 (acid) | [Drugbank](#main-references) | Acid dissociation constant |
| Solubility     | mg/L     | 17 (at pH 7) | [Drugbank](#main-references) | Aqueous solubility |
| fu<sub>plasma</sub> |   | 0.009     |[Takahashi 2003](#main-references)| Fraction unbound in plasma (albumin binding) |
| LogP          | –        | 3.46      |[Avdeef 1998](#main-references)| Liposomal mambrane/water partition coefficient |
| B/P           | –        | 0.55      | —          | Blood-to-plasma ratio (used in reduction pathway) |

**S-warfarin - Metabolic and clearance parameters**

| **Pathway / Enzyme** | **Parameter** | **Unit** | **Value** | **Source / Note** |
|:---------------------|:--------------|:---------|----------:|:------------------|
| CYP2C9               | Km            | µM       | 3.9       | [Shaik 2016](#5-references)  |
| CYP3A4               | Km            | µM       | 14.9      |  [Shaik 2016](#5-references) |
| Reduction to alcohols| Plasma CL     | ml/h/kg  | 0.14      |   |
| Reduction to alcohols| Specific CL   | 1/min    | 0.02      | Metabolism reduction mediated by aldo-keto reductases (i.e., Fm~10%) [Wittkowsky 2003](#5-references)|
| Renal clearance      | Plasma CL     | ml/h/kg  | 0.07      |   Consistent with fraction excreted in urine ~ 1% [FDA 2010](#main-references) |

**R-warfarin - Metabolic and clearance parameters**

| **Pathway / Enzyme** | **Parameter** | **Unit** | **Value** | **Source / Note** |
|:---------------------|:--------------|:---------|----------:|:------------------|
| CYP1A2               | Km            | µM       | 648       | Adopted from previous PK-Sim model |
| CYP2C19              | Km            | µM       | 391       | Adopted from previous PK-Sim model |
| CYP3A4               | Km            | µM       | 586       | Adopted from previous PK-Sim model |
| Reduction to alcohols| Specific CL   | 1/min    | 0.02      |   |
| Renal clearance      | Plasma CL     | ml/h/kg  | 0.07      |   |

### Clinical Data  <a id="clinical-data"></a>

A literature search was performed to collect available clinical data on Warfarin in healthy adults.

#### Model Building S-Warfarin <a id="model-building"></a>

The following studies were used for model building (training data):

| **Dose [mg]** | **Dosing** | **PK data** |**Dataset**| **Reference** |
| --------------- | ------------------- | ----------------------- | ----------------- |----------------- |
| 15| po, sd |plasma|training|[Soon 2006](#5-references)| 
| 25| po, sd |plasma|training|[Schwartz 2008](#5-references)| 

iv = intravenous; po = oral administration; tab = tablet administration; sd = single dose; qd = once daily

#### Model Verification S- Warfarin <a id="model-verification"></a>

The following studies were used for model verification:

| **Dose [mg]** | **Dosing** | **PK data** |**Dataset**| **Reference** |
| --------------- | ------------------- | ----------------------- | ----------------- |----------------- |
| 0.375| iv, tab, fasted, sd |plasma|verification|[O'Sullivan 1993](#5-references)| 
| 7.5| po, tab, fasted with meal administration 3h post-dose, sd |plasma|verification|[Frymoyer 2010](#5-references)| 
| 10| po, tab, fasted, sd |plasma|verification|[Kim 2001](#5-references)| 
| 10| po, tab, fasted, sd |plasma|verification|[Lilja 2007](#5-references)| 
| 10| po, tab, fasted, sd |plasma|verification|[Ngo 2010](#5-references)| 
| 10| po, tab, fasted, sd |plasma|verification|[Turpeinen 2013](#5-references)| 
| 13| po, tab, fed, sd |plasma|verification|[Weber 1999](#5-references)|
| 15| po, tab, fasted, sd |plasma|verification|[Schwartz 2009](#5-references)| 
| 20| po, tab, fasted, sd |plasma|verification|[Ouellet 2006](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Almeida 2008](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Dingemanse 2013](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[He 2007](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Macha 2013](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Malhotra 2011](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Rahimy 2002](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Sanwald Ducray 2014](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Stockis 2013](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Toon 2087](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Toon 1990](#5-references)| 
| 25| po, tab, fed, sd |plasma|verification|[Mallikaarjun 1999](#5-references)| 
| 25| po, tab, fed, sd |plasma|verification|[Sidharta 2014](#5-references)| 
| 25| po, tab, fed, sd |plasma|verification|[Soon 2006](#5-references)| 
| 25| po, tab, fed, sd |plasma|verification|[Yin 2011](#5-references)| 
| 30| po, tab, fed, sd |plasma|verification|[Liao 1996](#5-references)| 


iv = intravenous; po = oral administration; tab = tablet administration; sd = single dose; qd = once daily


#### Model Verification R- Warfarin <a id="model-verification"></a>

The following studies were used for model verification:

| **Dose [mg]** | **Dosing** | **PK data** |**Dataset**| **Reference** |
| --------------- | ------------------- | ----------------------- | ----------------- |----------------- |
| 25| po, tab, fasted, sd |plasma|verification|[Almeida 2008](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Dingemande 2013](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[He 2007](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Malhotra 2011](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Rahimy 2002](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Stockis 2013](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Toon 1987](#5-references)| 
| 25| po, tab, fasted, sd |plasma|verification|[Toon 1990](#5-references)| 
| 25| po, tab, fed, sd |plasma|verification|[Mallikaarjun 1999](#5-references)| 
| 25| po, tab, fed, sd |plasma|verification|[Sidharta 2014](#5-references)| 
| 25| po, tab, fed, sd |plasma|verification|[Soon 2006](#5-references)| 
| 25| po, tab, fed, sd |plasma|verification|[Yin 2011](#5-references)| 

iv = intravenous; po = oral administration; tab = tablet administration; sd = single dose; qd = once daily
