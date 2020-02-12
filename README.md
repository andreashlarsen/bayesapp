# bayesapp
calculates pair distance distribution function via Bayesian indirect Fourier transformaiton (BIFT)

### Online GUI at GenApp
https://somo.chem.utk.edu/bayesapp/

### Getting started
1) Compilation (linux):  gfortran -m32 -O2 iftci.f -o iftci    
    
2) Run:                  iftci < inputfile.d    
    
3) The file: inputfile.d has to contain the 14 lines:    

line 1:  the name of the data file  - compulsory -    
line 2:  value for q_min            or a blank line    
line 3:  value for q_max            or a blank line    
line 4:  value for d_max            or a blank line    
line 5:  value for eta              or a blank line    
line 6:  value for alpha            or a blank line    
line 7:  value for smearing const.  or a blank line    
line 8:  value for ratio            or a blank line    
line 9:  value for method           or a blank line    
line 10: value for no of points     or a blank line    
line 11: value for no of extra calc or a blank line    
line 12: value for transformation   or a blank line    
line 13: value for background       or a blank line    
line 14: value for screensize       or a blank line    

### Reference
 (1) https://scripts.iucr.org/cgi-bin/paper?pe0063    
 (2) https://onlinelibrary.wiley.com/iucr/doi/10.1107/S0021889812014318    
 (3) http://journals.iucr.org/j/issues/2014/04/00/he5656/    
 (4) https://scripts.iucr.org/cgi-bin/paper?gk0508    
