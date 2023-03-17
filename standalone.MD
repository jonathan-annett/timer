Manual Install Instructions
===

Windows (using nw.js)
---

* you'll need to download  2 zip files:

 the nw,js runtime files - either [win64](https://dl.nwjs.io/v0.74.0/nwjs-v0.74.0-win-x64.zip) or [win32](https://dl.nwjs.io/v0.74.0/nwjs-v0.74.0-win-ia32.zip) depending on your windows version (full list [here](https://nwjs.io/downloads/))

 the [timer.zip](timer.zip) file which contains the files for the timer app itself
  
 lets assume you intend to install the app into c:\timer:
 
 extract the nw.js zip file into c:\timer (you'll end up with a folder called something like `c:\timer\nwjs-v0.74.0-win-x64\`
 
 copy the timer.zip file to `c:\timer\timer.zip` (you don't need to extract it)
 
 navigate into the c:\timer\nwjs-v0.74.0-win-x64 and locate the nw.exe file
 
 create a desktop shortcut to this file and edit the arguments to add timer.zip as an argument
 
    `"c:\timer\nwjs-v0.74.0-win-x64\nw.exe" timer.zip`
 
