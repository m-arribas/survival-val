# survival-val
This repository provides the code used in the paper *"Development and Internal-External Validation of a Natural Language Processing-based Transdiagnostic Risk Calculator for Joint Detection of Psychosis and Bipolar Risk and Prediction of Outcomes in Clinical Practice"* (in press). The purpose of this project is to provide a **transparent** and **reproducible** method for analyzing the data presented in our publication, as well as making our code publically avaiable for researchers interested in developing multivariable prediction models within an internal-external validation framework with their own databases.

Steyerberg and Harrell recommend internal-external validation as an alternative to split-sample approaches, offering improved assessment of generalizability across subgroups or settings. In our case, data are split by geographical borough, with the model iteratively trained on a set of boroughs (derivation dataset) and validated on the excluded borough (validation dataset). The final model, developed on all available data, is considered internally-externally validated, providing coefficients for future external validation.

Please refer to Steyerberg EW, Harrell FE. Prediction models need appropriate internal, internal-external, and external validation. J Clin Epidemiol. 2016;69:245-247. doi:10.1016/j.jclinepi.2015.04.005 for further information on this statistical approach. 

### Data Sharing
The data accessed by CRIS remain within an NHS firewall and governance is provided by a patient-led oversight committee. However, due to data sharing policy (see https://doi.org/10.1186/1471-244X-9-51 for futher details) we are unable to share the raw data. 

### Data Files
All the data is generated synthetically at the start of the script. The analyses can be replicated with the synthetic dataset but the results will differ from our original results. 

## Getting Started
These instructions will guide you through setting up the project and running the analysis on your own machine.

### Installation
The scripts are all written in R. Please make sure you have installed the libraries which are loaded at the start of the script. 

### Running the Analysis
The code is all contained in the R markdown file.

## Contributing
Since this project is associated with a submitted manuscript, modifications might be limited. However, if you find any bugs or have suggestions, please open an issue in the repository.

## Authors
Maite Arribas: m-arribas

## License
This project is licensed under the Apache License - see the LICENSE.md file for details.
