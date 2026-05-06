# Qwt 6.1.3 Headers compatible with Qt6 and C++20
This repository serves to satisfy the rules of the Qwt License, under which a publication of the changes to Qwt code is required.

The files provided here are based on Qwt version 6.1.3. Only some header files needed update for the intended use case (keeping a library, compiled prior to Qt6 and C++20, in use, but linking it to projects using C++20 and deprecating Qt API before 6.0), so only the headers are included here. Please find the remaining source code in the official repository of the Qwt project (https://sourceforge.net/projects/qwt).

The changes of fix syntactical issue with templates and the construction of some optional arguments, and don't change the ABI. The changes are very similar to changes done to later version of Qwt but were sadly never provided for version 6.1.
