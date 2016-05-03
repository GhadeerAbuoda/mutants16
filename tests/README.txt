This directory has the raw test data, including statement coverage
(.cov files) and fault IDs (.rev files) for all GCC and SpiderMonkey
tests from PLDI 13 Chen et al.

Test cases are in .fmin files (final, minimized test).  For
SpiderMonkey, these need to be executed in conjunction with the
jsfunfuzz core code to define tryItOut, and for GCC they are simply C
files to be compiled.
