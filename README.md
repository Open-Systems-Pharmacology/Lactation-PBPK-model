# Lactation-PBPK-model

Whole body PBPK model to quantitatively predict ondansetron transfer into breast milk. 
 
### Repository Files

Within this repository, we built a lactation PBPK model using an ondansetron pregnancy model [[1-2](#References)] as a template. This model is evaluated using in vivo concentration data from plasma and breast milk in lactating women. Predictions were based on a virtual lactating population we developed that included anatomic and physiological changes that occur after delivery. Details on model building and evaluation have been published previously [[3](#References)].

This repository contains the MoBi<sup>®</sup> file with the lactation model structure (please note that this model is not correctly parameterized in terms of the postpartum anatomy and physiology). 

The postpartum/lactation anatomy and physiology is not integrated in the official release of the PK-Sim<sup>®</sup> database. Therefore a `sqlite` file with the anatomical and physiological parameters of postpartum individuals is distributed within this repository. Both files can used for importing and running a postpartum population simulation in the portable version of PK-Sim<sup>®</sup>. Please note that the `sqlite` file in this repository is only compatible with PK-Sim<sup>®</sup> version 9.1.

### Version Information

PK-Sim<sup>®</sup> Version 9.1
MoBi<sup>®</sup> Version 9.1

### License

The model is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

### Reference

[1][Dallmann A, Ince I, Coboeken K, Eissing T, Hempel G. A Physiologically Based Pharmacokinetic Model for Pregnant Women to Predict the Pharmacokinetics of Drugs Metabolized Via Several Enzymatic Pathways. Clin Pharmacokinet. Jun 2018;57(6):749-768. doi:10.1007/s40262-017-0594-5](https://pubmed.ncbi.nlm.nih.gov/28924743/).

[2][Open-Systems-Pharmacology/Pregnancy-Models.](https://github.com/Open-Systems-Pharmacology/Pregnancy-Models)

[3][Job KM, Dallmann A, Parry S, et al. Development of a Generic Physiologically Based Pharmacokinetic Model for Lactation and Prediction of Maternal and Infant Exposure to Ondansetron via Breast Milk. Clin Pharmacol Ther. Jan 25 2022;doi:10.1002/cpt.2530.](https://doi.org/10.1002/cpt.2530)
