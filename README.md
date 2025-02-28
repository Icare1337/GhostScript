This directory contains a test suite of malicious PostScript files.

version.ps can be used to discover the version of GhostScript running.

list_folder.eps can be used to list the directory in the permanent directory (On Windows, this is the current user's temporary files, on Linux, it is /tmp).

write_files.ps can be used to write a file in the permanent directory (On Windows, this is the current user's temporary files, on Linux, it is /tmp). Please note that the file you want to copy must be encoded in Base64.

read_files.ps can be used to read a file from the permanent directory (On Windows, this is the current user's temporary files, on Linux, it is /tmp).
