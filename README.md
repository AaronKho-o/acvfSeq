The acvfSeq package was created to determine if a symetric sequence is positive semidefinite. Any symmetric positive semidefinite sequence can act as the autocovariance function of a weakly stationary process. Thus, acvfSeq uses the tools in time series analysis. Inspiration comes from the ST304 course at LSE.


acvfSeq has methods which approach the problem in the time and frequency domain. In the former, it creates a toeplitz matrix with the sequence as its first row. In the latter, it aims to visualise the shape of the spectral distribution of a weakly stationary process.
