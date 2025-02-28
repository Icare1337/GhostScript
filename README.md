# Malicious PostScript Test Suite

This directory contains a test suite of malicious PostScript files.


## Files Description

- **`version.ps`**  
  Can be used to discover the version of GhostScript running.
  
![version.eps](https://raw.githubusercontent.com/Icare1337/GhostScript/refs/heads/main/version.png)

- **`list_folder.eps`**  
  Can be used to list the directory in the permanent directory.  
  - **Windows:** Current user's temporary files  
  - **Linux:** `/tmp`

- **`write_files.ps`**  
  Can be used to write a file in the permanent directory.  
  - **Windows:** Current user's temporary files  
  - **Linux:** `/tmp`  
  **Note:** The file you want to copy must be encoded in Base64.

- **`read_files.ps`**  
  Can be used to read a file from the permanent directory.  
  - **Windows:** Current user's temporary files  
  - **Linux:** `/tmp`
