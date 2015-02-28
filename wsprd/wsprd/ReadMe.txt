========================================================================
    CONSOLE APPLICATION : wsprd Project Overview
========================================================================

wsprd.exe - WSPR C decoder Windows port

This is Windows compatible port of the K9AN C port of the WSPR decoder.
It compilies with the free Visual Studio express. The two libs: libfftw3-3
and libsndfile-1 are dinamically linked, so you will need the dlls in the
program directory. Also to compile you might need to put the .lib files
in your VS libs directory, get them from converted_libs folder.

To add to WSPR-X:

- Close the program
- Rename the existing wsprd.exe to wsprd__.exe
- Put the new executable plus the two dlls into the WSPR-x directory
- Run as normal

-------------------------------
73!
K Atanassov, M0NKA
