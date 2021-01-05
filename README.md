# MoorDyn

## MoorDyn v1.01.01C

Copyright (c) 2014-2017 Matt Hall <mthall@upei.ca>

MoorDyn is free software: you can redistribute it and/or modify 
it under the terms of the GNU General Public License as published 
by the Free Software Foundation, either version 3 of the License, 
or (at your option) any later version.

MoorDyn is distributed in the hope that it will be useful, but 
WITHOUT ANY WARRANTY; without even the implied warranty of 
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU 
General Public License for details.

You should have received a copy of the GNU General Public License 
along with MoorDyn.  If not, see <http://www.gnu.org/licenses/>.

MoorDyn also contains source code from KISS FFT that will be used 
in future features.  The license for KISS FFT is included in the 
file kiss_fft_LICENSE.txt  


## General Notes

For information about using MoorDyn, see the included MoorDyn 
User's Guide, available at www.matt-hall.ca/moordyn.

For information about MoorDyn's formulation and some validation 
results, see M. Hall and A. Goupee, 'Validation of a lumped-mass 
mooring line model with DeepCwind semisubmersible model test 
data,' Ocean Engineering, vol. 104, pp. 590-603, Aug. 2015.  
(http://www.sciencedirect.com/science/article/pii/S0029801815002279)

The program, source code, and examples included with this readme
file pertain to "MoorDyn C", the version of MoorDyn written in 
C++, licensed under the GPL, and designed for coupling with a 
wide variety of tools.  The latest information about MoorDyn C 
can be found at the web page www.matt-hall.ca/moordyn.

This version of MoorDyn has been coupled to provide mooring
dynamics for the wave energy converter simulator WEC-Sim.  For 
more information, see http://wec-sim.github.io/WEC-Sim/

For information about MoorDyn F, the FORTRAN-based version that
is part of FASTv8, see nwtc.nrel.gov/MoorDyn


## Contents

The Examples folder contains minimal examples in Matlab and 
Simulink showing how these can be coupled with MoorDyn.  
They also include an example MoorDyn input file for the 
OC3-Hywind mooring system.

The DLL folders contain the compiled MoorDyn libraries for 32-bit 
and 64-bit Windows programs.  The appropriate DLL will need to be 
copied into the example folders for them to work.


