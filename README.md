# Overview 

Assessing Wind Power Forecasting Methods for Wind Energy Generation   
ME Thesis Project - ME Energy Systems Engineering UCD    
Author - Deignan   
May 2024    

# Description

This repository contains the data, codes and results used in ME thesis project: Assessing Wind Power Forecasting Methods for Wind Energy Generation. The aim of the project is to assess the robustness and portability of decomposition-based, artificial neural network wind power forecasting methods. Additionally, the ability of ChatGPT-4 to produce wind power forecasts is assessed.

Two wind farm SCADA datasets are used in this project (Kelmarsh and Penmanshiel wind farm, both situated in the UK). They are available under an CC-BY-4.0 open source license at [zenodo.org](https://zenodo.org/) You can find the data in this repository at:
```sh
/data
```

Missing values in these datasets were imputed using a kNN Imputer strategy. Two *.ipynb* Jupyter Notebook files have been used to do this. These files can also be found at:
```sh
/data
```

The forecasting outputs from the project are saved at:
```sh
/figures
```

The results of the portability analysis, including figures, are saved at:
```sh
/portability_results
```
The python script produced by ChatGPT-4 (after syntax and interface issues were ammended manually) is saved at:
```sh
/chtgpt_forecasting
```

# Note:

Some non-open source codes and data used in this project are not included in this repository. Additionally, the raw SCADA data files are not included due to file size constraints; they are available at [zenodo_penmanshiel.org](https://zenodo.org/records/5946808) and [zenodo_kelmarsh.org](https://zenodo.org/records/8252025).

# License
--
# Project Status
--
