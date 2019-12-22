# Usage
Grab the [TriIsoExtract.exe](bin/TriIsoExtract.exe?raw=true) and place it into a new folder.  
If you want to have .chd support get chdman.exe as well (needs to have CHD v5 support, just google chdman v146) and put it into the same folder as TriIsoExtract.exe.  
Drag and drop your raw binary/track 3 binary/chd file into TriIsoExtract.exe, it should then properly find the actual image in it and write it into a new .bin file.  
After you receive the new .bin file you can then use [triforce-hdr-patcher](https://github.com/FIX94/triforce-header-patcher) on it to get it ready for loaders such as Nintendont.  
This program should at least work with the following GD-ROMs in all their revisions:  
GDT-0001, GDT-0002, GDT-0004, GDT-0005, GDT-0006, GDT-0008, GDT-0009, GDT-0010, GDT-0011, GDT-0013, GDT-0014, GDT-0015, GDT-0017, GDT-0018, GDT-0019, GDT-0020, GDT-0021, GDT-0022


# Manual Compiling
~~As of right now this is a windows only code~~. 

## windows
If you have MinGW installed and gcc referenced in your PATH variable just use the "build.bat".  
Support for other OSes might follow in the future.

## linux
run build.sh, same chdman rules apply (see Usage) but get a linux version of chdman
