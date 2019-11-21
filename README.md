# BTCCD

Bundle of Matlab scripts is a GUI-based software for the Brightness-gated Two Color Coincidence (BTCCD) analysis of single molecule data from a confocal microscope

#### Downloading and installing BTCCD software
The BTCCD software requires Matlab licence (2015b or newer).
1. Download BTCCD software from https://github.com/BTCCD/BTCCD;
2. Unpack the files;
3. Start Matlab and make sure that BTCCD routines are visible for Matlab;
4. Call "TCCD" command in the command window.

#### Data format used by BTCCD software
Initially TTTR data aquisition format was converted to ASCII files. Input data is file(s) is an ASCII code where each line represents a photon. 
Columns represent
1st column: Channel number;
2nd column: Macro time (in ns);
3rd column: Micro time (in number of time bins since last laser excitation).

 
