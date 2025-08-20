The general concept of building a PBPK model has previously been described by Kuepfer et al. ([Kuepfer 2016](#5-references)). Relevant information on anthropometric (height, weight) and physiological parameters (e.g. blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in adults was gathered from the literature and has been previously published ([Willmann 2007](#5-references)). The information was incorporated into PK-Sim® and was used as default values for the simulations in adults.

The applied activity and variability of plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available PK-Sim® Ontogeny Database Version ([PK-Sim Ontogeny Database Version 7.3](#5-references)) or otherwise referenced for the specific process.

A PBPK model was built based on seven mean plasma concentration-time profiles after oral administration of atorvastatin acid obtained from the clinical studies by Backman 2005 ([Backman 2005](#5-references)), Bullman 2011 ([Bullman 2011 ](#5-references)), Gandelman 2011 ([Gandelman 2011](#5-references)), Kantola 1998 ([Kantola 1998](#5-references)) and Teng 2013 ([Teng 2013](#5-references)). To inform CYP3A4- and OATP1B1/1B3-mediated pathways, the DDI studies with itraconazole ([Kantola 1998](#5-references)) and rifampicin ([Lau 2007](#5-references)) were included in the model building. Virtual mean individuals were generated for each study based on the reported mean and mode demographic information (including sex, ethnicity, body weight, height, body mass index, and age). If demographic information was missing, provided mean values in PK-Sim®, that were computed from the respective population database, were applied. The relative tissue-specific expressions of the enzyme and transporter predominantly being involved in the metabolism/transport of atorvastatin acid (CYP3A4, CYP3A5, BCRP, OATP1B1/1B3, and P-gp) were considered ([Nishimura 2003](#5-references), [Nishimura 2005](#5-references), [Kolesnikov 2015](#5-references)). 

A specific set of parameters (see [Section 3.1](#31-atorvastatin-acid-final-input-parameters)) was optimized to describe the disposition of atorvastatin acid using the Parameter Identification module provided in PK-Sim®.

The model was then verified by simulating further clinical studies reporting pharmacokinetic concentration-time profiles after oral administration of atorvastatin acid.

Details about input data (physicochemical, *in vitro* and clinical) can be found in [Section 2.2](#22-data-used).

Details about the structural model and its parameters can be found in [Section 2.3](#23-model-parameters-and-assumptions).



