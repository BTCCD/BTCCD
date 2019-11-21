# BTCCD

BTCCD is a GUI-based software for the Brightness-gated Two Color Coincidence Detection (BTCCD) analysis of single molecule data from a confocal microscope.

#### Downloading and installing BTCCD software
The BTCCD software requires Matlab license (2015b or newer).
1. Download BTCCD software from https://github.com/BTCCD/BTCCD;
2. Unpack the files;
3. Start Matlab and make sure that BTCCD routines are visible for Matlab;
4. Call "TCCD" command in the command window.

#### Data format used by BTCCD software
Initially TTTR data acquisition format was converted to ASCII files. Input data is file(s) is an ASCII code where each line represents a photon. 
Columns represent
1st column: Channel number;
2nd column: Macro time (in ns);
3rd column: Micro time (in number of time bins since last laser excitation).

 #### Sample data for BTCCD analysis
 Sample data include single-molecule measurement of double-stranded double-labeled DNA of 48 base pairs, 5'-modified with Alexa488 and 3'-modified with Atto647N. This is a reference sample for BTCCD close to 100% coincidence presented in the publication Höfig H., et al. (2019) Brightness-Gated Two-Color Coincidence Detection Unravels Two Distinct Mechanisms in Bacterial Protein Translation Initiation (manuscript submitted for publication).

## Further information
For detailed description of the BTCCD method refer to the publication Höfig H., et al. (2019) Brightness-Gated Two-Color Coincidence Detection Unravels Two Distinct Mechanisms in Bacterial Protein Translation Initiation (manuscript submitted for publication).

To report bugs of suggestions use the "Issues" function on GitHub.
