# Evolution of the West African Monsoon under different CO<sub>2</sub> net-zero stabilisation pathways

The data used for this project is located under the group workspaces **epoc** and **TerraFirma** on JASMIN. As the datasets are not included in this repository, the code provided here is intended to document the analysis workflow used to process and analyse the data on JASMIN. Some file paths and data-access steps may therefore need to be adapted to reproduce the analysis elsewhere.


## 1. Evaluation of the West African Monsoon in UKESM

The first component of the project evaluates how realistically the West African Monsoon (WAM) is represented in UKESM simulations. Model precipitation, temperature and wind fields are compared against observational and reanalysis datasets, including GPCP and ERA5. The notebooks associated with this part of the project are named `model_bias_analysis`.

## 2. WAM Evolution under CO<sub>2</sub> Net-Zero Stabilisation

The second component investigates how the WAM evolves following CO<sub>2</sub> net-zero stabilisation at different global warming levels using the TerraFirma/TIPMIP simulations. The notebooks beginning with `ramp_and_run` contain the climatological analysis, while those beginning with `decomposition` and `ramp_up_decomposition` contain the precipitation decomposition.
