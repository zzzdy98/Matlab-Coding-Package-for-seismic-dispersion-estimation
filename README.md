## Description
Matlab Coding Package for frequency-dependent elastic impedance (FEI) inversion based on the L-BFGS algorithm, frequency-dependent elastic modulus calculation, and elastic modulus dispersion parameter estimation.

The L-BFGS algorithm implementation follows the method proposed by Ahmed et al. (2022), which can be downloaded from: https://github.com/nahmed215/avoinversion.git. 
Note: The downloaded L-BFGS algorithm files should be added to the MATLAB path before running the code.

## Reference
N. Ahmed, W. W. Weibull, and D. Grana, “Constrained non-linear AVO inversion based on the adjoint-state optimization,” Comput. Geosci., vol. 168, pp. 105214, Nov. 2022, doi: 10.1016/j.cageo.2022.105214.

## Reproducibility
This package contains two primary MATLAB scripts:
1) Main_FEI.m
2) Main_Dispersion.m

A test well-log model file Log_model.mat is provided.
The required subfunctions for FEI inversion and plotting are included in the Subfunctions folder.

Workflow:
1) Download the L-BFGS algorithm from the above repository.
2) Add the downloaded L-BFGS folder and the provided Subfunctions folder to the MATLAB path.
3) Load the test input dataset Log_model.mat.
4) Run Main_FEI.m — this generates the FEI inversion results.
5) Run Main_Dispersion.m — this uses FEI outputs to compute frequency-dependent elastic moduli and dispersion parameters.

## Environment Requirements
MATLAB R2015 or later versions.

## Contact
For any questions, please contact:
Danyu Zhao
zhaody23@mails.jlu.edu.cn
