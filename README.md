# Awesome Fortran [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome Fortran frameworks, libraries and software. Inspired by [awesome-swift](https://github.com/Wolg/awesome-swift) by @Wolg.

- [Awesome Fortran](#awesome-fortran)
	- [Graphics Libraries](#graphics-libraries)
	- [Math libs](#math-libs)
	- [JSON Manipulation](#json-manipulation)
	- [XML Manipulation](#xml-manipulation)
	- [Date and time manipulation](#date-and-time-manipulation)
	- [Testing](#testing)
	- [Encoding-Decoding](#encoding-decoding)
  - [Portability enabling](#portability-enabling)
  - [Command-Line parsing](#command-line-parsing)
  - [Compiling and building](#compiling-and-building)
  - [Preprocessor](#preprocessor)
  - [Automatic documentation](#automatic-documentation)
  - [Computational Fluid Dynamics](#computational-fluid-dynamics)
- [Resources](#resources)
  - [Fortran Websites](#fortran-websites)
	- [Fortran Videos](#fortran-videos)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Graphics Libraries
*Libraries for graphing, graphics, and GUIs*

* [DISLIN](http://www.mps.mpg.de/dislin/) - a high-level graphing and user-interface library.
* [f90gl](http://math.nist.gov/f90gl/) - public domain implementation of the official NIST Fortran 90 bindings for OpenGL.
* [F03GL](http://www-stone.ch.cam.ac.uk/pub/f03gl/index.xhtml) - a Fortran 2003 interface to the OpenGL library, along with the GLU and GLUT toolkits.
* [gtk-fortran](https://github.com/jerryd/gtk-fortran/wiki) - a cross-platform library to build Graphical User Interfaces (GUI) using [GTK+](http://www.gtk.org/).  Very useful when combined with the [Glade](https://glade.gnome.org/) RAD tool.
* [PGPLOT](http://www.astro.caltech.edu/~tjp/pgplot/) - cross-platform scientific graphing library.
* [Lib_VTK_IO](https://github.com/szaghi/Lib_VTK_IO) - Pure Fortran (2003+) library to write and read data conforming the VTK standard.

## Math Libs
*Libraries for calculating and other mathematical operations.*

* [BLAS](http://www.netlib.org/blas/) - application programming interface standard for publishing libraries to perform basic linear algebra operations such as vector and matrix multiplication.
* [CERNLIB](http://cernlib.web.cern.ch/cernlib/) - The CERN Program Library is a large collection of general purpose libraries and modules maintained and offered in both source and object code form on the CERN central computers
* [EISPACK](http://www.netlib.org/eispack/) - a software library for numerical computation of eigenvalues and eigenvectors of matrices, written in FORTRAN
* [FGSL](http://www.lrz.de/services/software/mathematik/gsl/fortran/index.html) - portable, object-based Fortran interface to the [GNU scientific library](http://www.lrz.de/services/software/mathematik/gsl/)
* [IMSL](http://www.roguewave.com/products-services/imsl-numerical-libraries/fortran-libraries) - The IMSL Fortran Numerical Library is the standard for high performance computing commercial mathematics and statistics libraries
* [Lis](http://www.ssisc.org/lis/index.en.html#download) - a Library of Iterative Solvers for Linear Systems
* [NAG Fortran Library](http://www.nag.co.uk/numeric/fl/FLdescription.asp) - Produced by experts for use in a variety of applications, the NAG Fortran Library has a global reputation for its excellence and, with hundreds of fully documented and tested routines, is the largest collection of mathematical and statistical algorithms available
* [netCDF](https://github.com/Unidata/netcdf-fortran) - a set of software libraries and self-describing, machine-independent data formats that support the creation, access, and sharing of array-oriented scientific data.
* [OpenBLAS](https://github.com/xianyi/OpenBLAS) - one of the fastest open source BLAS libraries available.  Almost as fast as Intel MKL.
* [PAW](http://paw.web.cern.ch/paw/) - conceived as an instrument to assist physicists in the analysis and presentation of their data

## JSON Manipulation
*Libraries for JSON data manipulating with Fortran language.*

* [FSON](https://github.com/josephalevin/fson) - Fortran 95 JSON Parser.
* [json-fortran](https://github.com/jacobwilliams/json-fortran) - A Fortran 2008 JSON API.

## XML Manipulation
*Libraries for XML data manipulating with Fortran language.*

* [fox](https://github.com/andreww/fox) - Fortran XML library
* [xml-fortran](http://sourceforge.net/projects/xml-fortran/) - an all-Fortran solution for reading and writing XML files.

## Date and time manipulation
*Libraries for date and time manipulation with Fortran language.*

* [datetime-fortran](https://github.com/milancurcic/datetime-fortran) - A Fortran 2003 date and time manipulation library, modeled after Python's datetime library.

## Testing
*Libraries for testing codebases and generating test data.*

* [FRUIT](http://sourceforge.net/projects/fortranxunit/) - FORTRAN Unit Test Framework, written in FORTRAN 95
* [Ftunit](http://flibs.sourceforge.net/ftnunit.html) - Fortran unit testing framework by Arjen Markus
* [pFUnit](http://sourceforge.net/projects/pfunit/) - Unit testing framework for Fortran with MPI extensions by developers from NASA and NGC TASC.  Uses parallel codes and object-oriented design.

## Encoding-Decoding
*Libraries for encoding and decoding data with Fortran language.*

* [BeFoR64](https://github.com/szaghi/BeFoR64) - Base64 encoding/decoding library for FoRtran poor men. A KISS library for base64 encoding/decoding for modern (2003+) Fortran projects.

## Portability enabling
*Libraries for enabling codes portability.*

* [IR_Precision](https://github.com/szaghi/IR_Precision) - Pure Fortran (2003+) library for ensuring codes portability.

## Command-Line parsing
*Libraries for parsing command-line and building user interfaces.*

* [FLAP](https://github.com/szaghi/FLAP) - Fortran command Line Arguments Parser for poor men. A KISS library for building easily nice Command Line Interfaces (CLI) for modern (2003+) Fortran projects.
* [options.f90](https://github.com/cngilbreth/optionsf90) - Options & input processing for modern Fortran.

## Compiling and building
*Libraries for compiling and building Fortran projects.*

* [FoBiS](https://github.com/szaghi/FoBiS) - Fortran Building System for poor men. A KISS tool for automatic building modern Fortran projects.

## Preprocessor
*Libraries for conditional-compilation, macros for code simplification, and inclusion of additional source files, templating systems.*

* [Blockit/PyF95++](http://blockit.sourceforge.net/) - A fairly simple Python framework used to block parse your code (or any text file) into nested blocks. The BlockIt framework has already been used to create a templating capability for the Fortran 95/2003 language along with some language extensions.
* [PreForM](https://github.com/szaghi/PreForM) - Preprocessor for Fortran poor Men.

## Automatic documentation
*Libraries for building documentation.*

* [FORD](https://github.com/cmacmackin/ford) - An automatic documentation generator for modern Fortran programs.

## Computational Fluid Dynamics
*Libraries for CFD computations*

* [OFF](https://github.com/szaghi/OFF/tree/testing) - Open source Finite volume Fluid dynamics code.

# Resources
Various resources, such as books, websites and articles, for improving your Fortran development skills and knowledge.

## Fortran Websites

* [The Fortran Company](http://www.fortran.com/) - A home page of FORTRAN programming language.
* [Fortran Dev](https://fortrandev.wordpress.com/) - Fortran development blog.
* [Fortran WIKI](http://fortranwiki.org/fortran/show/HomePage) - An open venue for discussing all aspects of the Fortran programming language and scientific computing.

## Fortran Videos

* [GNU FORTRAN Lesson 1](https://www.youtube.com/watch?v=qUy8M10uZRU) - Videos about the Fortran programming language.

# Other Awesome Lists

Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

# Contributing

Your contributions are always welcome! Please submit a pull request or create an issue to add a new framework, library or software to the list. Do not submit a project, which hasn't been updated in the past 6 months or is not awesome.
