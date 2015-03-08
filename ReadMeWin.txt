========================================================================
    CONSOLE APPLICATION : wsprd Project Overview
========================================================================

wsprd.exe - WSPR C decoder Windows port v 0.0.1.5, 08 March 2015

This is Windows compatible port of the K9AN C port of the WSPR decoder.
It compilies with the free Visual Studio express. The two libs: libfftw3-3
and libsndfile-1 are dinamically linked, so you will need the dlls in the
program directory. Also to compile you might need to put the .lib files
in your VS libs directory, get them from converted_libs folder.

To add to WSPR-X:

- Close the program
- Rename the existing wsprd.exe to wsprd__.exe
- Put the new executable plus the two dlls into the WSPR-x directory
- Double click on wsprd.exe to see if all ok, if you get error starting,
you need runtime libs from MS site (http://www.microsoft.com/en-us/download/details.aspx?id=30679)
- Run WSPR-X as normal

Releases:

v 1.5, 08 March 2015

- Fixed a problem that affected extended callsigns with a 2-character suffix(sync with k9an master)

v 1.4, 03 March 2015

- frequency precision changed in the all_wspr.txt to reflect
the K9AN master

v 1.3, 03 March 2015

- crlf fixed in all_wspr.txt and logging as well
- added latest changes from main K9AN code
- bug fix on open of .wav file (extra mem allocation)

v 1.2, 01 March 2015

- fixed Windows XP compatibility

v 1.1, 28 Feb 2015

- first release 

-------------------------------
73!
K Atanassov, M0NKA
