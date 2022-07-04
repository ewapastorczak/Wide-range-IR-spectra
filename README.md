The goal of this package is to semiautomatically assign IR bands in diarylethene spectra and also to assess how good a DFT functional simulating the spectra is for this purpose.
If you wish to use the package with different spectra than provided here, prepare:
1) A .csv file with the experimental spectrum as in Sheet1_68_closed_ok.csv with columns: first, with wavenumbers in cm-1 and the other with peak heights. The spectrum does not need to be normalized.
2) One or more simulated spectra files. The allowed inputs are consistent with GaussView exported widened IR spectra. The HWHM used were 4cm-1, however in general they can take different values.
