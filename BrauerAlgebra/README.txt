****************************************
          Short presentation
****************************************

The package BrauerAlgebra encodes several aspects of the Brauer algebra and of the Symmetric group algebra. Its goal is twofold : 
1) provide an efficient tool for mathematicians and physicists in the study of the Brauer algebra on its own 
2) take advantage of the richness of this algebra for applications in theoretical physics. 
From a practical point a view this package was developed to optimize particular operation in tensor calculus. 
For example, it provides an efficient construction of the traceless projectors for tensors on a Riemannian/Symplectic manifold. 
The proofs for the traceless projector algorithm used in this package can be found in :  "Traceless projection of tensors via the Brauer algebra" D.V. Bulgakova, Y.O.  Goncharov, T. Helpin. 

Via the xBrauer companion package, BrauerAlgebra is link to the xAct (xTensor) bundle for tensorial calculus (José M. Martin-Garcia, GPL 2002-2022) which is widely used in theoretical physics. http://www.xAct.es/

To work properly the package requires the package SymmetricFunctions.

Author: Thomas Helpin. Affilated to the Institut Denis Poisson (France).


****************************************
          INSTALLATION NOTES 
****************************************


When uncompressed, the archive files give a number of files hanging
from a directory called BrauerAlgebra/. This directory must be placed at
(or linked from) one of the places Mathematica prepares for external
applications in the xAct directory. You can find the actual paths in your Mathematica
installation in the variables $BaseDirectory and $UserBaseDirectory.
You need the Applications/ subdirectory (or subfolder) of those
returned by those variables.

Linux:

   - system-wide installation (requires root priviledges):

        /usr/share/Mathematica/Applications/xAct

   - single-user installation:

        $HOME/.Mathematica/Applications/xAct

Mac OS:

   - system-wide installation (requires root priviledges):

        /Library/Mathematica/Applications/xAct

   - single-user installation:

        /Users/<user>/Library/Mathematica/Applications/xAct

MSWindows:

   - system-wide installation:

	C:\Program Files\Wolfram Research\Mathematica\<version>\AddOns\Applications\xAct\

   - single-user installation:

	C:\Users\<user>\AppData\Roaming\Mathematica\Applications\xAct\

   Beware that in Windows these directories might be hidden!


Documentation files and exemples (like Tutorial_Examples_BrauerAlgebra.nb, etc) are placed in the xAct/BrauerAlgebra/Documentation directory.

Then the packages can be loaded using unix style

        <<xAct/BrauerAlgebra/BrauerAlgebra.m

or Mathematica style

        <<xAct`BrauerAlgebra`

If you have any problem, don't hesitate to contact me at

thomas.helpin@gmail.com


