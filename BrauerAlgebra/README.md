# BrauerAlgebra


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

This package needs the SymmetricFunctions package to work properly. 

Author: Thomas Helpin. Affilated to the Institut Denis Poisson (France).


****************************************
          INSTALLATION NOTES 
****************************************

After extracting the archive, you'll find multiple files contained within a directory named BrauerAlgebra-$BranchName/. 
Rename this directory to BrauerAlgebra/ and place it in a location where Mathematica looks for external packages. 
To find these locations, check the values of $BaseDirectory and $UserBaseDirectory in your Mathematica installation. 
Specifically, you'll need to move the renamed directory into the Applications/ subdirectory of either of these paths.

For Wolfram Language versions before 14.1 use Mathematica instead of
Wolfram in the following links.

Linux:

   - system-wide installation (requires root priviledges):

        /usr/share/Wolfram/Applications/

   - single-user installation:

        $HOME/.Wolfram/Applications/

Mac OS:

   - system-wide installation (requires root priviledges):

        /Library/Wolfram/Applications/

   - single-user installation:

        /Users/<user>/Library/Wolfram/Applications/

MSWindows:

   - system-wide installation:

	C:\Program Files\Wolfram Research\Wolfram\<version>\AddOns\Applications\

   - single-user installation:

	C:\Users\<user>\AppData\Roaming\Wolfram\Applications\

   Beware that in Windows these directories might be hidden!


Documentation files and exemples (like Tutorial_BrauerAlgebra.nb, etc) are placed in the BrauerAlgebra/Documentation directory.

The packages can be loaded using unix style

        <<BrauerAlgebra/BrauerAlgebra.m

or Mathematica style

        <<BrauerAlgebra`

If you have any problem, don't hesitate to contact me at

thomas.helpin@gmail.com


