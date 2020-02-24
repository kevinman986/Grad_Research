# Grad_Research
All Fortran90 code herin was written by Kevin Anderson. Some included C code was initially written by Eran Rabani. 

## Summary 
This code was used to model single exciton decay in n-type group II-VI semiconducting nanoparticles. Cadmium Selenide was the primary use, but the theories and approximations would allow for any group II-VI semiconductor with minimal reparameterization. The main part of the code is written to the Fortran90 specification. Included BLAS libraries were hand-coded to be optimized specifically for the Lonestar supercomupting cluster at the University of Texas. More general mkl libiraries or appropriate libraries found on the local cluster would likely lead to better performance.

## Setup
This program was written and configured with gcc in mind, but other Fortran compilers would likely work as well. Most needed configuration items will be found in the Makefile. 


