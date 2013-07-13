AssimpViewerLinux
=================

Assimp Viewer on Linux


This program is enable to view the textured model on Linux platform.


This program requires below libraries.

* Open Asset Import Library (Assimp) http://assimp.sourceforge.net/index.html
* free-glut http://freeglut.sourceforge.net/
* Developer's Image Library http://openil.sourceforge.net/



How to Use
-------------------------
1. git clone https://github.com/tkada/AssimpViewerLinux/ AssimpViewerLinux
2. cd AssimpViewerLinux/SimpleOpenGL
3. make
4. ./samplegl (Model File Path)


Troubleshooting
--------------------------
* ./samplegl: error while loading shared libraries: libassimp.so.3: cannot open shared object file: No such file or directory  
Add environment variable.  
`export LD_LIBRARY_PATH=/usr/local/lib`



