# chakra.dll Info Leak + Type Confusion for RCE


Proof-of-Concept exploit for Edge bugs (CVE-2016-7200 & CVE-2016-7201)

Tested on Windows 10 Edge (modern.ie stable).

FillFromPrototypes_TypeConfusion.html: WinExec notepad.exe

FillFromPrototypes_TypeConfusion_NoSC.html: 0xcc (INT 3)

# To run

1. Download exploit/FillFromPrototypes_TypeConfusion.html to a directory.
2. Serve the directory using a webserver (or python's simple HTTP server).
3. Browse with a victim IE to FillFromPrototypes_TypeConfusion.html.
