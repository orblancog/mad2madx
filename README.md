Beta release

++ USE

$ mad2madx madline

it creates a file "madline.madx"

++ WARNINGS

Multipoles were complicated to translate. I haven't seen any bug, but use carefully.
PROFILE elements do not exist in MAD-X, they are changed to MARKER elements.

++TESTS

It has only been tested with Mark Woodley's Flight simulator MAD files

https://confluence.slac.stanford.edu/display/ATF/ATF2+Flight+Simulator

I took the .saveline MAD file from here (v5.2)

https://code.google.com/p/atf2flightsim/source/browse/#svn%2Ftrunk%
2FATF2%2FFlightSim%2FlatticeFiles%2Fsrc%2Fv5.2

and I used this code to translate from MAD to MADX

This is the result (THIS IS THE LINE YOU ASKED)

/afs/cern.ch/work/o/oblancog/public/progs/MAD-X/2MAD-X/ATF2lat_BX10BY1nl.saveline.madx

There are 4 lines declared: ATFDR, EXT, FF, POST
I guess it is 10BX1BY1 from the name.

oscar

p.s. I have used my own translation script, I haven't
seen any bug, but let me know if you see any strange behaviour
