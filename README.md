# CompositionalIGFoam

This is a solver developed on top of the `porousMultiphaseFoam` project for compositional flow modeling in porous media. It includes a new solver for .

## Origin

This code is based on [porousMultiphaseFoam](https://github.com/horgue/porousMultiphaseFoam), originally developed by Horgue et al. (2015).

# General Informations

- This toolbox needs only a standard OpenFOAM installation
  (see www.openfoam.org or www.openfoam.com)

- Please cite the related paper in the "doc" folder if you are using this
  toolbox.

- Read the COPYING_OPENFOAM file for information about OpenFOAM and this
  toolbox Copyrights.

# Installation instructions :

- First, source the OpenFOAM configuration file, i.e. (example for ubuntu
  version) :

> source /opt/openfoamv6/etc/bashrc

- then in the "porousMultiphaseFoam" directory, run :

> ./Allwmake -jX

  to install the package (with X the number of processors).

- Dynamic libraries are compiled in the standard OpenFOAM user directory :

> $FOAM_USER_LIBBIN

- The executable solver "impesFoam" is placed in the standard OpenFOAM user
  directory $FOAM_USER_APPBIN.

- Each tutorial directory contains "run" and "clean" files to test installation
  and validate the solver.

- A python script runTutorials.py can be used to test all components.

- To remove compilation and temporary files, run :

> ./Allwclean

- see the ReleaseNotes.txt file for detailed information about the toolbox.

---
