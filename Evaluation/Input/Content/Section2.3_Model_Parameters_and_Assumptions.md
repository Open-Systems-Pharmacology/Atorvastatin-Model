### 2.3.1 Absorption

A parameter value for  `Specific intestinal permeability` and a measured solubility at pH=6 sourced from the literature were incorporated into the model (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)). Additionally, a solution formulation was selected (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)).

### 2.3.2 Distribution

Atorvastatin acid is highly bound to plasma proteins (approx. 94.9%) (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)). A value of 5.10% was used in the PBPK model for `Fraction unbound (plasma, reference value)`. The major binding partner was set to albumin (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)).

An important parameter influencing the resulting volume of distribution is lipophilicity. The reported literature logP value of 4.07 was used in the model (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)). 

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim®, observed clinical data was best described by choosing the partition coefficient calculation by `Schmitt` and cellular permeability calculation by `Charge dependent Schmitt`.

### 2.3.3 Metabolism and Elimination

Two metabolic pathways were implemented into the model via Michaelis-Menten kinetics: 

* CYP3A4

The CYP3A4 expression profile is based on high-sensitive real-time RT-PCR ([Nishimura 2003](#18-references)). Metabolic enzyme activity was described as saturable process following Michaelis-Menten kinetics, where the `Km` was taken from the literature and the `kcat` was optimized based on clinical data (see [Section 2.3.4](#234-automated-parameter-identification)).

* CYP3A5

The CYP3A5 metabolic pathway was implemented only for normal metabolizers in the study by [Park 2022](#28-references); for all other studies, CYP3A5 `kcat` value was set to 0.
The CYP3A5 expression profile is based on high-sensitive real-time RT-PCR ([Nishimura 2003](#18-references)). Metabolic enzyme activity was described as saturable process following Michaelis-Menten kinetics, where the `Km` was taken from the literature and the `kcat` was optimized based on clinical data (see [Section 2.3.4](#234-automated-parameter-identification)).

In addition, three transport proteins were implemented into the model via Michaelis-Menten kinetics: 

* BCRP

The BCRP expression profile is based on whole genome expression arrays from ArrayExpress ([Kolesnikov 2015](#5-references)). Transporter activity was described as saturable process following Michaelis-Menten kinetics, where the `Km` was taken from the literature and `kcat` was optimized based on clinical data (see [Section 2.3.4](#234-automated-parameter-identification)).

* OATP1B1/1B3

For OATP1B1/1B3 the expression profile was considered only for OATP1B1 and is based on high-sensitive real-time RT-PCR ([Nishimura 2005](#20-references)). Transporter activity was described as saturable process following Michaelis-Menten kinetics, where the `Km` was taken from the literature and `kcat` was optimized based on clinical data (see [Section 2.3.4](#234-automated-parameter-identification)).

* P-gp

The P-gp expression profiles is based on high-sensitive real-time RT-PCR ([Nishimura 2005](#20-references)) with an intestinal mucosa of factor 3.57 ([Hanke 2018](#27-references)). Transporter activity was described as saturable process following Michaelis-Menten kinetics, where the `Km` was taken from the literature and `kcat` was optimized based on clinical data (see Section 2.3.4).

Additionally, fraction of bile that was continuously released was set to 1 (`EHC continuous fraction`).


### 2.3.4 Automated Parameter Identification

This is the result of the final parameter identification:

| Model Parameter                | Optimized Value | Unit      |
| ------------------------------ | --------------- | --------- |
| `kcat` (CYP3A4)                | 8.57            | 1/min     |
| `kcat` (CYP3A5) NM             | 1350.42         | 1/min     |
| `kcat` (CYP3A5) PM/IM          | 0               | 1/min     |
| `kcat` (BCRP)                  | 932.28          | 1/min     |
| `kcat` (OATP1B1/1B3)           | 1970.16         | 1/min     |
| `kcat` (P-gp)                  | 614.28          | 1/min     |

IM, intermediate metabolizer; NM, normal metabolizer; PM, poor metabolizer.
