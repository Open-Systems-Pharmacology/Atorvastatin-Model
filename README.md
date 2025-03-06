# Atorvastatin-Model
Whole-body PBPK model of atorvastatin acid.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/Atorvastatin.svg/2560px-Atorvastatin.svg.png" alt="File:Atorvastatin.svg" style="zoom:50%;" />

This repository contains:

- a [PK-Sim snapshot (*.json) file](https://docs.open-systems-pharmacology.org/working-with-pk-sim/pk-sim-documentation/importing-exporting-project-data-models#exporting-project-to-snapshot-loading-project-from-snapshot) of the current PBPK model
- static content (e.g. text blocks, *.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation-plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model

**The latest release of the snapshot of the model, the evaluation plan and the static content can be found [here](../../releases/latest).**

**The latest release of the PK-Sim project model file and the respective evaluation report can be found [here](https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library/releases/latest).**

Within this repository, we share a whole-body PBPK model of atorvastatin acid that has been carefully developed using clinical studies by Backman 2005 ([Backman 2005](#8-references)), Bullman 2011 ([Bullman 2011](#3-references)), Di Spirito 2008 ([Di Spirito 2008](#4-references)), Gandelman 2011 ([Gandelman 2011](#1-references)), Kantola 1998 ([Kantola 1998](#10-references)), Lau 2007 ([Lau 2007](#11-references)), Mazzu 2000 ([Mazzu 2000](#5-references)), Mori 2020 ([Mori 2020](#12-references)), Park 2022 [Park 2022](#28-references), Patiño-Rodríguez 2015 ([Patiño-Rodríguez 2015](#2-references)), Shin 2011 ([Shin 2011](#6-references)), Siedlik 1999 ([Siedlik 1999](#7-references)), Takehara 2018 ([Takehara 2018](#13-references)), Teng 2013 ([Teng 2013](#14-references)) and Whitfield 2010 ([ Whitfield 2010](#9-references)) after oral administration. The selected clinical study data captures a broad dosing range of 1.0 to 80.0 mg atorvastatin acid.

The PK-Sim project file contains simulations and the observed data of all clinical studies used for model development and evaluation.

## Code of conduct

Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution

We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License

The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## References

[1] Gandelman K, Malhotra B, LaBadie RR, Crownover P, Bergstrom T. Analytes of Interest and Choice of Dose: Two Important Considerations in the Design of Bioequivalence Studies with Atorvastatin. Journal of Bioequivalence & Bioavailability, 3(4):062–068, 2011.
[2] Patiño-Rodríguez O, Martínez-Medina RM, Torres-Roque I, Martínez-Delgado M, Mares-García AS, Escobedo-Moratilla A, Covarrubias-Pinedo A, Arzola-Paniagua A, Herrera-Torres JL, Pérez-Urizar J. Absence of a significant pharmacokinetic interaction between atorvastatin and fenofibrate: a randomized, crossover, study of a fixed-dose formulation in healthy Mexican subjects. Front Pharmacol., 6(4), 2015.
[3] Bullman J, Nicholls A, Van Landingham K, Fleck R, Vuong A, Miller J, Alexander S, Messenheimer J. Effects of lamotrigine and phenytoin on the pharmacokinetics of atorvastatin in healthy volunteers. Epilepsia, 52(7):1351–8, 2011.
[4] Di Spirito M, Morelli G, Doyle RT, Johnson J, McKenney J (2008) Effect of omega-3-acid ethyl esters on steady-state plasma pharmacokinetics of atorvastatin in healthy adults. Expert Opin Pharmacother., 9(17):2939–45, 2008.
[5] Mazzu AL, Lasseter KC, Shamblen EC, Agarwal V, Lettieri J, Sundaresen P. Itraconazole alters the pharmacokinetics of atorvastatin to a greater extent than either cerivastatin or pravastatin. Clin Pharmacol Ther., 68(4):391–400, 2008.
[6] Shin J, Pauly DF, Pacanowski MA, Langaee T, Frye RF, Johnson JA. Effect of cytochrome P450 3A5 genotype on atorvastatin pharmacokinetics and its interaction with clarithromycin. Pharmacotherapy, 31(10):942–50, 2011.
[7] Siedlik PH, Olson SC, Yang BB, Stern RH. Erythromycin coadministration increases plasma atorvastatin concentrations. J Clin Pharmacol., 39(5):501–4, 1999.
[8] Backman JT, Luurila H, Neuvonen M, Neuvonen PJ. Rifampin markedly decreases and gemfibrozil increases the plasma concentrations of atorvastatin and its metabolites. Clin Pharmacol Ther., 78(2):154–67, 2005.
[9] Whitfield LR, Porcari AR, Alvey C, Abel R, Bullen W, Hartman D. Effect of gemfibrozil and fenofibrate on the pharmacokinetics of atorvastatin. J Clin Pharmacol., 51(3):378–88, 2010.
[10] Kantola T, Kivistö KT, Neuvonen PJ. Effect of itraconazole on the pharmacokinetics of atorvastatin. Clin Pharmacol Ther., 64(1):58–65, 1998.
[11] Lau YY, Huang Y, Frassetto L, Benet LZ. Effect of OATP1B transporter inhibition on the pharmacokinetics of atorvastatin in healthy volunteers. Clin Pharmacol Ther., 81(2):194–204, 2007.
[12] Mori D, Kimoto E, Rago B, Kondo Y, King-Ahmad A, Ramanathan R, Wood LS, Johnson JG, Le VH, Vourvahis M, David Rodrigues A, Muto C, Furihata K, Sugiyama Y, Kusuhara H. Dose-Dependent Inhibition of OATP1B by Rifampicin in Healthy Volunteers: Comprehensive Evaluation of Candidate Biomarkers and OATP1B Probe Drugs. Clin Pharmacol Ther., 107(4):1004–1013, 2020.
[13] Takehara I, Yoshikado T, Ishigame K, Mori D, Furihata KI, Watanabe N, Ando O, Maeda K, Sugiyama Y, Kusuhara H. Comparative Study of the Dose-Dependence of OATP1B Inhibition by Rifampicin Using Probe Drugs and Endogenous Substrates in Healthy Volunteers. Pharm Res., 35(7):138, 2018.
[14] Teng R, Mitchell PD, Butler KA. Pharmacokinetic interaction studies of co-administration of ticagrelor and atorvastatin or simvastatin in healthy volunteers. Eur J Clin Pharmacol., 69(3):477–87, 2013.


