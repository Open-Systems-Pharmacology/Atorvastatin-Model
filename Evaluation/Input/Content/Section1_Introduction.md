Atorvastatin, a 3-hydroxy-3-methylglutaryl-coenzyme A (HMG-CoA) reductase inhibitor, is a widely prescribed statin to treat hypercholesterolemia ([Morse 2019](#5-references)). The recommended dosage for adults ranges from 10 to 80 mg once daily ([Pfizer 2019](#5-references)). Following oral administration, atorvastatin acid is rapidly absorbed from the gastrointestinal tract, reaching maximum plasma concentrations within one to two hours ([Pfizer 2019](#5-references)). However, its bioavailability is notably low (~14%) due to extensive first pass metabolism by cytochrome P450 (CYP) 3A4 ([Pfizer 2019](#5-references)). Atorvastatin acid is also a substrate of multiple transporters, including the influx transporters organic anion transporting polypeptides (OATP) 1B1 and OATP1B3 ([Vildhede 2014](#5-references)), as well as the efflux transporters P-glycoprotein (P-gp) and breast cancer resistant protein (BCRP) ([Deng 2021](#5-references)), which makes atorvastatin acid highly susceptible to drug–drug interactions (DDIs) mediated by both enzymes and transporters. 

This whole-body atorvastatin acid PBPK model is intended to be used as a victim drug in CYP3A4- and OATP1B1/1B3-mediated DDIs. It has been developed using published pharmacokinetic clinical data by Backman 2005 ([Backman 2005](#5-references)), Bullman 2011 ([Bullman 2011](#5-references)), Di Spirito 2008 ([Di Spirito 2008](#5-references)), Gandelman 2011 ([Gandelman 2011](#5-references)), Kantola 1998 ([Kantola 1998](#5-references)), Lau 2007 ([Lau 2007](#5-references)), Mazzu 2000 ([Mazzu 2000](#5-references)), Mori 2020 ([Mori 2020](#5-references)), Park 2022 [Park 2022](#5-references), Patiño-Rodríguez 2015 ([Patiño-Rodríguez 2015](#5-references)), Shin 2011 ([Shin 2011](#5-references)), Siedlik 1999 ([Siedlik 1999](#5-references)), Takehara 2018 ([Takehara 2018](#5-references)), Teng 2013 ([Teng 2013](#5-references)) and Whitfield 2010 ([ Whitfield 2010](#5-references)) after oral administration. The selected clinical study data captures a broad dosing range of 1.0 to 80.0 mg atorvastatin acid. 

The model has then been evaluated by simulating clinical studies and comparing with respective observed data. 

The presented model includes the following features:

- Metabolism by CYP3A4,
- Metabolism by CYP3A5 (only implemented in Park 2022 for CYP3A5 normal metabolizers ([Park 2022](#5-references)); otherwise, the kcat has been set to 0),
- Transport by BCRP,
- Transport by P-gp, and
- Transport by OATP1B1/1B3.


