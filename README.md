log-file-info
=============

COM component that can be registered in MS Windows 7/8 x64. 
It extends system shell to provide:

1. Add menu item to weite information about selected files into the log file.

2. Eash line in the log file consists of short filename, size and data in human readable form.

3. Lines append into the log file.

4. Lines is sorted by file names in alphabetical order.

5. In additional, it needs to calculate a per­byte sum (a flavour of checksum) in 4 bytes
variable (DWORD) for each file.

6. Component works on huge amout of selected files.
