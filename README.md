# AutoCAD Map 3D
.NET AutoCAD Map 3D 2019 Applications

VB/C# AutoCAD Map 3D applications that can be downgraded/upgraded to other versions of AutoCAD Map 3D.

How?

In Visual Studio, open the "Project Properties" window and do the following:

- "Application" tab: Change the required AutoCAD Map 3D 20## .NET version (Target Framework: .NET Framework #.#)

- "Reference Paths" tab: Change the reference paths to point to the correct versions of "inc" (and/or "inc-x64") DLL's from the .NET API(s) you downloaded from the Autodesk Developer's Network. For example, I use my D: drive and have a path like this for the base references:

D:\Autodesk\AutoCAD Map Development\AutoCAD2019\inc

D:\Autodesk\AutoCAD Map Development\AutoCAD2019\inc-x64

  and for Map specific references (aka 'includes'):

D:\Autodesk\AutoCAD2018Map3D\Inc

D:\Autodesk\AutoCAD2018Map3D\Inc-X64
  
Credit and great appreciation go to: https://github.com/JanKallman/EPPlus - I have used EPPlus in place of my Visual LISP routines
to read from Excel Worksheets in a custom "DXF shotpoints - to - AutoCAD Block" convertor program.  If you need this type of functionality, I recommend you considering using AutoCAD Civil 3D as it provides much more functionality, especially when the clients change their minds…
