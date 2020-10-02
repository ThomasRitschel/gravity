# gravity


Numerical Model to Simulate Gravity-Driven Soil Aggregation and Colloidal Self-Assembly

Instructions to gravity_aggregation_3D.exe
------------------------------------------
supporting executable to manuscript "Mechanistic modeling and 3D exploration of gravity-constrained aggregation in natural aqueous systems" by Tom Guhra, Thomas Ritschel and Kai Uwe Totsche


General Information
-------------------
64-Bit Win executable

Compiled from source.txt, linear_algebra.txt, and Screen3DRequester.txt with PureBasic 5.60

gravity_aggregation_3D.exe.exe creates init.dat upon first run to store user settings


Dependencies
------------

A recent Version of DirectX 9 is required. If program crashes, install http://www.microsoft.com/en-us/download/details.aspx?id=35.

The executable depends on the OGRE Engine (https://www.ogre3d.org/) that is licensed with an MIT Open Source Licence

https://github.com/OGRECave/ogre/blob/master/LICENSE

To include the OGRE Engine, simply copy Engine3D.dll in the same folder as gravity_aggregation_3D.exe 


System requirements
-------------------
64-Bit CPU, source code contains x64-assembly, no 32-Bit compatibility 


Installation
------------
execute gravity_aggregation_3D.exe as is, no installation required, include Engine3D.dll to the folder

Demo
----
1. execute gravity_aggregation_3D.exe
2. test parameters are already set und should be as shown in settings.png
3. click "Start"
4. aggregation modeling starts and a window visualising the progress is created (screenshot.png)
5. hit ESC to quit and export 3D structure as stacked 2D images if required (folder .\aggregateout is created at location of execution and its content overridden)

run-time is depending on user and output is non-deterministic due to the stochastic nature of diffusion modeling 
