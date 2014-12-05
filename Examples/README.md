Example output files from various programs that support the NEF.  Each program directory contains subdirectories of examples.
  For sequential files, a short name of the program, followed by a dash, is prepended to the file.  The originating program uses an underscore.  
For example: ccpn writes a file called `ccpn_test.nef`.  Aria reads that file and writes out `aria-ccpn_test.nef`.  
This way, we can observe an otherwise silent problem arising from ccpn if we compare: `rosetta-ccpn-aria_test.nef` and `rosetta-aria_test.nef`.
