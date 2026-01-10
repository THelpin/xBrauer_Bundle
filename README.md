# xBrauer_Bundle
The xBrauer package needs BrauerAlgebra SymmetricFunctions and the xAct bundle (in particular xPerm, xTensor, Invar, SymManipulator, xTras) to work properly. 
It is specially useful for the trace decomposition and irreducible decomposition of a tensor. 


BrauerAlgebra and SymmetricFunctions are Wolfram Mathematica packages extensions
while xBrauer is an xAct extension. 


****************************************
          INSTALLATION NOTES 
****************************************


When uncompressed, the archive file give a number of directories (BrauerAlgebra/, SymmetricFunctions/ and xBrauer/) 
hanging from a directory called xBrauer_Bundle-main/. 

The two Wolfram Mathematica packages directories BrauerAlgebra/, SymmetricFunctions/ 
must me placed in a location where Mathematica looks for external packages.
For example, $HOME/.Wolfram/Applications/ for Linux single user installation.

The xAct extension folder xBrauer/ must be placed at one of the places Mathematica prepares for external
applications inside the xAct directory. 

For Wolfram Language versions before 14.1 use Mathematica instead of
Wolfram in the following links.


Linux:

   - system-wide installation (requires root priviledges):

        /usr/share/Wolfram/Applications/xAct/

   - single-user installation:

        $HOME/.Wolfram/Applications/xAct/

Mac OS:

   - system-wide installation (requires root priviledges):

        /Library/Wolfram/Applications/xAct/

   - single-user installation:

        /Users/<user>/Library/Wolfram/Applications/xAct/

MSWindows:

   - system-wide installation:

	C:\Program Files\Wolfram Research\Wolfram\<version>\AddOns\Applications\xAct\

   - single-user installation:

	C:\Users\<user>\AppData\Roaming\Wolfram\Applications\xAct\

   Beware that in Windows these directories might be hidden!


If you have any problem, don't hesitate to contact me at

thomas.helpin@gmail.com
