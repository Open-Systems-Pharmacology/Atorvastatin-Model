### 2.2.1 In vitro and physicochemical data

A literature search was performed to collect available information on physicochemical properties of atorvastatin acid. The obtained information from the literature is summarized in the table below, and is used for model building.

| **Parameter**             | **Unit** | **Value** | Source                               | **Description**                                              |
| :------------------------ | -------- | --------- | ------------------------------------ | ------------------------------------------------------------ |
| MW                        | g/mol    | 558.66    | [Zhang 2015](#5-references)         | Molecular weight                                             |
| pK<sub>a</sub> (acid)     |          | 4.46      | [Zhang 2015](#5-references)         | Acid dissociation constant of conjugate acid                 |
| Solubility (pH=6)         | g/L      | 1.22      | [Morse 2019](#5-references)         | Solubility                                           |
| logP                      |          | 4.07      | [Duan 2017](#5-references)          | Partition coefficient between octanol and water              |
| fu                        | %        | 5.10      | [Zhang 2015](#5-references)         | Fraction unbound in plasma                                   |
| K<sub>m</sub> CYP3A4      | µmol/L   | 25.60     | [Jacobsen 2000](#5-references)      | CYP3A4 Michaelis-Menten constant                             |
| K<sub>m</sub> CYP3A5      | µmol/L   | 42.60     | [Park 2008](#5-references)          | CYP3A5 Michaelis-Menten constant                             |
| K<sub>m</sub> BCRP        | µmol/L   | 82.41     | [Deng 2021](#5-references)          | BCRP Michaelis-Menten constant                               |                
| K<sub>m</sub> OATP1B1/1B3 | µmol/L   | 0.77      | [Vildhede 2014](#5-references)      | OATP1B1/3 Michaelis-Menten constant                         |
| K<sub>m</sub> P-gp        | µmol/L   | 10.7      | [Deng 2021](#5-references)          | P-gp Michaelis-Menten constant                                |
| Formulation               |          | Solution  |                                      | Formulation used in simulations                              |

### 2.2.2 Clinical data

A literature search was performed to collect available clinical data on atorvastatin acid in adults. 

The following publications were found in adults for model building:

| Publication                     | Arm / Treatment / Information used for model building        |
| :------------------------------ | :----------------------------------------------------------- |
| [Gandelman 2011](#5-references) | Plasma PK profile in healthy subjects after single oral administration of 10 mg atorvastatin acid (study A<sup>a</sup>) |
| [Bullman 2011](#5-references)   | Plasma PK profile in healthy subjects after multiple oral administrations of 40 mg atorvastatin acid (once daily for 7 days, control of DDI with phenytoin)|
| [Backman 2005](#5-references)   | Plasma PK profile in healthy subjects after single oral administration of 20 mg atorvastatin acid (control of gemfibrozil DDI) |
| [Kantola 1998](#5-references)  | Plasma PK profile in healthy subjects after single oral administration of 40 mg atorvastatin acid (control of itraconazole DDI) |
| [Kantola 1998](#5-references)  | Plasma PK profile in healthy subjects after multiple oral administrations of 200 mg itraconazole (once daily for 4 days) and on day 4 together with a single oral administration of 40 mg atorvastatin acid (itraconazole DDI) |
| [Lau 2007](#5-references)      | Plasma PK profile in healthy subjects after single oral administration of 40 mg atorvastatin acid, preceded by 30 minutes infusion of 600 mg rifampicin (rifampicin DDI) |
| [Teng 2013](#5-references)     | Plasma PK profile in healthy subjects after single oral administration of 80 mg atorvastatin acid |



The following dosing scenarios were simulated and compared to respective data for model verification:

| Scenario                                                     | Data reference                        |
| ------------------------------------------------------------ | ------------------------------------- |
| single oral administration of 1  mg atorvastatin acid (control of rifampicin DDI)| [Mori 2020](#5-references)           |
| single oral administration of 1  mg atorvastatin acid (control of rifampicin DDI)| [Takehara 2018](#5-references)       |
| single oral administration of 10 mg atorvastatin acid (study C<sup>a</sup>)                | [Gandelman 2011](#5-references)       |
| single oral administration of 10 mg atorvastatin acid (control of erythromycin DDI)| [Siedlik 1999](#5-references)         |
| single oral administration of 20 mg atorvastatin acid (control of itraconazole DDI)| [Mazzu 2020](#5-references)           |
| single oral administration of 20 mg atorvastatin acid            | [Patiño-Rodríguez 2015](#5-references)|
| single oral administration of 20 mg atorvastatin acid (control of clarithromycin DDI in the CYP3A5 expressor group)       | [Shin 2011](#5-references)            |
| single oral administration of 20 mg atorvastatin acid (control of clarithromycin DDI in the CYP3A5 non-expressor group)    | [Shin 2011](#5-references)            |
| single oral administration of 40 mg atorvastatin acid (control of rifampicin DDI)  | [Backman 2005](#5-references)         |
| single oral administration of 40 mg atorvastatin acid (control of gemfibrozil DDI) | [Whitfield 2011](#5-references)       |
| multiple oral administrations of 40 mg atorvastatin acid (once daily for 7 days)       | [Bullman 2011](#5-references)         |
| single oral administration of 40 mg atorvastatin acid (control of rifampicin DDI)| [Lau 2007](#5-references)            |
| multiple oral administrations of 80 mg atorvastatin acid (once daily for 14 days)      | [Di Spirito 2008](#5-references)      |
| single oral administration of 80 mg atorvastatin acid (study B<sup>a</sup>)                | [Gandelman 2011](#5-references)       |
| single oral administration of 80 mg atorvastatin acid (study D<sup>a</sup>)                | [Gandelman 2011](#5-references)       |
| single oral administration of 80 mg atorvastatin acid (CYP3A5 normal metabolizer) | [Park 2022](#5-references)            |
| single oral administration of 80 mg atorvastatin acid (CYP3A5 intermediate metabolizer) | [Park 2022](#5-references)            |
| single oral administration of 80 mg atorvastatin acid (CYP3A5 poor metabolizer) | [Park 2022](#5-references)            |

<sup>a</sup>  In the study by [Gandelman 2011](#5-references), a small tablet formulation (1x10 mg in study A and 1x80 mg in study B) and a chewable tablet
formulation (1x10 mg in study C and 1x80 mg in study D) was tested in two single-dose bioequivalent studies (10 mg and
80 mg). Only the plasma profiles of the reference product in each study were digitized. 
