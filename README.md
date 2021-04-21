**Introduction**
The acvfSeq package was created to determine if a symmetric sequence is positive semidefinite. Any symmetric positive semidefinite sequence can act as the autocovariance function of a weakly stationary process. Thus, acvfSeq uses the tools in time series analysis. Inspiration comes from the ST304 course at LSE.

acvfSeq has methods which approach the problem in the time and frequency domain. In the former, it creates a toeplitz matrix with the sequence as its first row. In the latter, it aims to visualise the shape of the spectral distribution of a weakly stationary process.


**Usage** 

library(devtools)

install_github("AaronKho-o/acvfSeq")


**Functions**

tmatrix_psd: Prove a sequence is not positive semidefinite.

spec_density: Obtain values of spectral density for a range of frequencies.

spec_density_plot: Plot values of spectral density for a range of frequencies.

convert_complex_exp: Returns arguments of complex exponential form for complex data types.


_See vignettes folder for examples and more detail on functions._

