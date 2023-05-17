****************************************
          Short presentation
****************************************


The xBrauer package is an extension of the xAct Bundle  http://www.xAct.es/ (José M. Martin-Garcia, GPL 2002-2022). To work properly this package needs the following packages 
From the xAct bundle : xPerm, xTensor, Invar, SymManipulator. 
Independent package coming with xBrauer : SymmetricFunctions, BrauerAlgebra. 


The goal of this package is to take advantage of the mathematics of the Brauer algebra for applications in tensor calculus.  For example, it provides an efficient construction of the traceless projectors for tensors on a Riemannian/Symplectic manifold. The proofs for the traceless projector algorithm used in this package can be found in :  "Traceless projection of tensors via the Brauer algebra" D.V. Bulgakova, Y.O.  Goncharov, T. Helpin. 

More generaly with this package you can easily perform : the trace decomposition of a tensor, the explicit irreducible decomposition of a tensor with respect to action of GL(dim) and O(dim). 
Some tools to work on a symplectic manifold has been added. 

Author: Thomas Helpin. Affilated to the Institut Denis Poisson (France).


****************************************
          INSTALLATION NOTES 
****************************************


When uncompressed, the archive files give a number of files hanging
from a directory called xBrauer/. This directory must be placed at
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


Documentation files and examples (like RiemannianManifold.nb, etc) are placed in the xBrauer/Documentation directory.

Then the packages can be loaded using unix style

        <<xAct/xBrauer/xBrauer.m

or Mathematica style

        <<xAct`xBrauer`

If you have any problem, don't hesitate to contact me at

thomas.helpin@gmail.com


