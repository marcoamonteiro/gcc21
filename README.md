# gcc21

This program accepts a payment of 1000 satoshi in return for compiling a C file.

Running "./gcc21 [filename.c] [flags] [executable file name]",  Uploads [filename.c], and compiles it with the flags in [flags].
The executable is downloaded to [executable file name]

Here is a sample command:

./gcc21 test.c -o testexecutable

To run the server, run the command ./sever
