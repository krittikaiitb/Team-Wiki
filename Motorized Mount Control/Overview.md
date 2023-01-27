## iOptron CEM26 Computer Control Guide


Software Required:
- N.I.N.A (NIGHTTIME IMAGING 'N' ASTRONOMY) [Link (use latest stable)](https://nighttime-imaging.eu/download/) 

N.I.N.A acts as an higher level interface to control a diverse set of mounts, cameras and other astrophotography gear. It's basically a fancy GUI to interact with the uglier low level stuff which is not very usable. It's competely free and open source and that makes it one of the most amazing software packages in the amateur astronomy world. Also download the "Three Point Polar Alignment" plugin after launching N.I.N.A.
- ASTAP 64-bit version and H17 star database [Link](https://www.hnsky.org/astap.htm)

ASTAP is used for [plate solving](https://en.wikipedia.org/wiki/Astrometric_solving#:~:text=Astrometric%20solving%20or%20Plate%20solving,stars%20and%20a%20star%20catalogue.). This is a method of measuring the exact pointing orientation of the mount, and correcting the often erroneous location the mount "thinks" it is oriented in. N.I.N.A supports many different software packages that can platsolve, but ASTAP is the nicest. The star catalogue must be downloaded and installed separately, and is a pretty big download. Watch [this video](https://www.youtube.com/watch?v=lAMyEpBcLV4) for a run through of platesolving.
- .NET Framework 4.8 [Link](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48)
- ASCOM Platform (Latest) [Link](https://www.ascom-standards.org/)

ASCOM (an abbreviation for AStronomy Common Object Model) is an open initiative to provide a standard interface to a range of astronomy equipment including mounts, focusers and imaging devices in a Microsoft Windows environment.
- iOptron Commander and ASCOM Driver Installer 6.3 or later [Link](https://www.ioptron.com/Articles.asp?ID=332)

This is the low-level software made by iOptron, the mounts manufacturer, to send basic control signals to the mount via USB or WiFi (yes, this works but sucks - use wires). While controlling the mount, we do not have to interact with this much. It directly talks to N.I.N.A and does the magic.


