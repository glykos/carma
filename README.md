# carma
A molecular dynamics analysis program
____________________________________________________________________

1. Go to bin/ subdirectory and see if you can find an executable
   suitable for your machine.
   If not, you will have to build carma from source as described in
   the documentation and the src/README file.

   Windows users can use the 'grcarma' installer which will install
   both carma & grcarma. Windows users would probably prefer working
   through 'grcarma' which offers a familiar graphical interface.


2. Try your executable with your DCD file to make sure it compiled
   without problems : 

   carma -v -fit <myDCD> <myPSF>          (assuming CA atoms exist)

   If your executable is graphics-enabled (MacOSX & Linux), try 

   carma <myDCD> <myPSF>

   If everything goes as planned, continue. If not, please do
   mail me a description of the problem.


3. Place the executable in a suitable directory (eg. /usr/local/bin)
   and/or define a symbol for it. Copy also the 'grcarma' and 
   'cluster5D' executables in the same directory so that anyone 
   wanting to use the graphical user interface can do so.


4. Go to the doc/pdf/ subdirectory and have a look or print the
   documentation. You can also add a bookmark in your browser 
   pointing to the doc/html/carma.html file. A unix manual page
   is also available (in the man/ subdirectory).

5. For support, please write to the carma mailing list at

     http://groups.google.com/group/carma-molecular-dynamics

____________________________________________________________________

