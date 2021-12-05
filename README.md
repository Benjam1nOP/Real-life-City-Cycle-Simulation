# Real-life-City-Cycle-Simulation
Dev C++ used:
https://sourceforge.net/projects/orwelldevcpp/
For openGL setup:
Step1: Extract the files in freeglut-MSVC-3.0.0-2.mp.zip
Step3: Paste files from C:\Users\laksh\Downloads\freeglut-MSVC-3.0.0-2.mp\freeglut\include\GL to C:\Program Files (x86)\Dev-Cpp\MinGW64\x86_64-w64-mingw32\include\GL
Step4: Paste files from C:\Users\laksh\Downloads\freeglut-MSVC-3.0.0-2.mp\freeglut\lib\x64 to C:\Program Files (x86)\Dev-Cpp\MinGW64\x86_64-w64-mingw32\lib
Step5: Paste files form C:\Users\laksh\Downloads\freeglut-MSVC-3.0.0-2.mp\freeglut\bin\x64 to C:\Windows\System32
Now Open Dev C++ create new project -> Console Application
Right click on project go to project options-> Parameters
Paste this in the Linker Column:
-lopengl32
-lfreeglut
-lglu32
Click OK.
All done Paste the Code.
