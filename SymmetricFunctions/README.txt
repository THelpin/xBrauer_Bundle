****************************************
          Short presentation
****************************************

The package SymmetricFunctions encodes the most standard symmetric functions basis (elementary, complete homegeneous, power sum, monomial and Schur) and their associated polynomial. The changes of basis between symmetric functions and the operation of plethysm is also implemented. Many associated combinatorial tools are present in the package (Young Tableaux, Littlewood Richardson coefficients, Kostka coefficients ...). A significant part of the algorithms is actually borrowed and adapted from the packages of Per Alexandersson is actually borrowed and adapted from the packages of Per Alexandersson https://github.com/PerAlexandersson?tab=repositories

This package is necessary for the packages BrauerAlgebra and xBrauer to work properly. 

Author: Thomas Helpin. Affilated to the Institut Denis Poisson (France).


****************************************
          INSTALLATION NOTES 
****************************************


When uncompressed, the archive files give a number of files hanging
from a directory called SymmetricFunctions/. This directory must be placed at
(or linked from) one of the places Mathematica prepares for external
applications in the xAct directory. You can find the actual paths in your Mathematica
installation in the variables $BaseDirectory and $UserBaseDirectory.
You need the Applications/ subdirectory (or subfolder) of those
returned by those variables.

Linux:

   - system-wide installation (requires root priviledges):

        /usr/share/Mathematica/Applications/xAct/

   - single-user installation:

        $HOME/.Mathematica/Applications/xAct/

Mac OS:

   - system-wide installation (requires root priviledges):

        /Library/Mathematica/Applications/xAct/

   - single-user installation:

        /Users/<user>/Library/Mathematica/Applications/xAct/

MSWindows:

   - system-wide installation:

	C:\Program Files\Wolfram Research\Mathematica\<version>\AddOns\Applications\xAct\

   - single-user installation:

	C:\Users\<user>\AppData\Roaming\Mathematica\Applications\xAct\

   Beware that in Windows these directories might be hidden!


Documentation files and exemples (like Tutorial_SymmetricFunctions.nb, etc) are placed in the SymmetricFunctions/Documentation directory.

Then the packages can be loaded using unix style

        <<xAct/SymmetricFunctions/SymmetricFunctions.m

or Mathematica style

        <<xAct`SymmetricFunctions`

If you have any problem, don't hesitate to contact me at

thomas.helpin@gmail.com


