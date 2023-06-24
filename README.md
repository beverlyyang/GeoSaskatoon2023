# GeoSaskatoon2023
The following files were used for the analyses in the GeoSaskatoon 2023 paper titled "The importance of data quantity in machine learning: how small is too small?" (Yang et al., 2023). Random forest (RF) regression models were developed on varying dataset sizes (ranging from 100 to 4950 with a step of 50) and with varying train/test splits to investigate the impact of data quantity on machine learning (ML) model results. The data used in this analysis was synthetic data generated from Rocscience's SWedge program using a probabilistic Monte Carlo analysis. Surrogate modelling was used, whereby the inputs of the SWedge program are the inputs of the RF models and the output of the SWedge program is the output of the RF models. Additional details can be found below and in the GeoSaskatoon 2023 paper:
<li>SWedge Input.xlsx file is the input file for probabilistic analysis in Rocscience's SWedge program.</li>
<li>GeoSaskatoon 2023 Code.ipynb file is the code used for the ML modelling.</li>
<li>SWedge Results.xlsx file is the input file for ML modelling (GeoSaskatoon 2023 Code.ipynb).</li>
<li>GeoSaskatoon 2023 ML Results.xlsx file is the file containing the output of the ML modelling code (GeoSaskatoon 2023 Code.ipynb) and the processed results and graphs used in the paper.</li>
<li>ML Inputs: slope face dip, slope face dip dir, joint 1 dip, joint 1 dip dir, joint 2 dip, joint 2 dip dir, joint 1 friction angle, joint 2 friction angle.</li>
<li>ML Output: safety factor.</li>
<li>ML Input Distributions: normal (slope face dip, slope face dip dir, joint 1 friction angle, joint 2 friction angle), fisher distribution with k = 40 (joint 1 dip/dip dir, joint 2 dip/dip dir).</li>
