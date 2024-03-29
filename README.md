# gravity


Numerical Model to Simulate Gravity-Driven Soil Aggregation and Colloidal Self-Assembly

Instructions to aggregation_modeler_3D.exe
------------------------------------------
supporting executable to manuscript "The mechanisms of gravity-constrained aggregation in natural colloidal suspensions" by Tom Guhra, Thomas Ritschel and Kai Uwe Totsche


General Information
-------------------
64-Bit Win executable (Win 10 preferred)

Compiled from source.txt, linear_algebra.txt, and Screen3DRequester.txt with PureBasic 5.60

if not already exisiting, aggregation_modeler_3D.exe creates init.dat upon first run to store user settings

GAEA.exe was used to aggregate the (sometimes massive) simulation output

Dependencies
------------

A recent Version of DirectX 9 is required. If program crashes, install http://www.microsoft.com/en-us/download/details.aspx?id=35.

The executable depends on the OGRE Engine (https://www.ogre3d.org/) that is licensed with an MIT Open Source Licence

https://github.com/OGRECave/ogre/blob/master/LICENSE

To include the OGRE Engine, simply copy Engine3D.dll in the same folder as aggregation_modeler_3D.exe 


System requirements
-------------------
64-Bit CPU, source code contains x64-assembly, no 32-Bit compatibility 


Tested on:
----------
Win 10 64 Bit, 32/20/16 GB RAM


Installation
------------
execute aggregation_modeler_3D.exe as is, no installation required, include Engine3D.dll to the folder and install DirectX End-User Runtime if needed.

Installation time is below 5 minutes typically.

Demo
----
1. execute aggregation_modeler_3D.exe
2. test parameters are stored in init.dat and will be automatically imported if placed in the same folder
3. click "Start"
4. aggregation modeling starts and a window visualising the progress is created, controls are shown on screen
5. hit ESC to quit and follow instructions to export wanted datasets

run-time is depending on user settings and output is non-deterministic due to the stochastic nature of diffusion modeling 
