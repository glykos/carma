# carma
A molecular dynamics analysis program
____________________________________________________________________


## Introduction

Carma is a stand-alone molecular dynamics analysis tool tuned for the DCD-PSF
world. The program is free, open-source software and is immediately available
for download via this page. Carma can calculate the variance-covariance and
cross-correlation matrices, do a principal component analysis using both
Cartesian PCA and dihedral angle PCA, do a PCA-based cluster analysis, remove
overall rotations/translations, calculate the mass-weighted radius of gyration,
calculate the average CA-CA distance map and the rmsd from it (for the length
of the trajectory), calculate the average structure and atomic rms
fluctuations, calculate distances and torsion angles between arbitrary sets of
atoms, calculate solute's entropy using both Schlitter's and Andricioaei's
formulas, allow a primitive quick view of a trajectory on a X11-capable
terminal, calculate CNS- and XPLOR-compatible density maps representing the
average distribution of selected atomic species (eg. ions or waters), etc.

grcarma is a graphical user interface to carma and automates many of the common 
tasks during the analysis of molecular dynamics trajectories.


## Installation for Linux

Inside the `bin/linux` directory of the distribution you can find the linux installer 
(with the extension .run). Executing this self-extracting archive (possibly 
with root privileges) will install everything in `/usr/local`. Stand-alone 
executables are also available in the `bin/linux/stand-alone/` directory.

For some of grcarma's additional features to work properly, you need to install the `tcsh` shell, 
and weblogo (with something like `pip3 install weblogo`).



## Installation for other platforms


1. Go to bin/ subdirectory and see if you can find an executable
   suitable for your machine.
   If not, you will have to build carma from source as described in
   the documentation and the src/README file.

   Windows users can use the 'grcarma' installer which will install
   both carma & grcarma. Windows users would probably prefer working
   through 'grcarma' which offers a familiar graphical interface.


2. Try your executable with your DCD file to make sure it compiled
   without problems : 

   `carma -v -fit <myDCD> <myPSF>`          (assuming CA atoms exist)

   If your executable is graphics-enabled (MacOSX & Linux), try 

   `carma <myDCD> <myPSF>`

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

