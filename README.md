# Millfork-C256Foenix
Target file info, so Millfork can compile to the C256 Foenix platform

Copy the c256_experimental.ini file to the include/platform folder inside your Millfork installation.

To compile run Millfork with:

millfork.exe YOURPROGRAM.mfk -t c256_experimental -s

Right now you can't use more the the first 64k of RAM, Millfork does not support 24bit addressing with the 65816 CPU.

Code will be placed at $2000.
