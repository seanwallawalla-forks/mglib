See documentation of the API for the routines in this library in::

  api-userdocs/index.html

Most of the routines in this library are ``.pro`` code that can easily be added
to ``IDL_PATH``, but there are some routines that are written in C that should
be compiled. See ``INSTALL.rst` ` for instructions on how to build the C DLM's
in this library.

The contents of the library are:

./
  startup file
analysis/
  various algorithms (sorting, sampling, etc.) and math helper routines
animation/
  classes to produce animations using object graphics
calendar/
  routines to deal with dates/times
cmdline_tools/
  routines useful at the IDL command line
collection/
  objects implementing various types of collections
cula/
  CULAtools bindings
dist_tools/
  routines for logging, preferences, and other miscellaneous routines useful
  in distributing applications
dist_tools/bindings/
  routines for wrapping C routines with a DLM in a quick and nearly an
  automatic manner using the `MG_DLM` class
dist_tools/cidl
  routines for creating hybrid C/IDL routines
envi/
  ENVI user routines
fileio/
  file input/output routines
googlevoice/
  class for connecting to Google Voice
gsl/
  wrappers for GNU Scientific Library (GSL) routines
hdf/
  routines for reading/writing/querying HDF files
hdf5/
  routines for reading/writing/querying HDF5 files
indices/
  routines for handling index arrays
install_tools/
  routines for installing new projects and their dependencies
introspection/
  routines for inspecting variables and routines
itools/
  iTools related helpers and components
markdown/
  wrapper for a C implementation of John Gruber's markdown
misc/
  miscellaneous routines
net/
  routines for handling network communication
objects/
  classes for doing object-oriented programming
profiling/
  helper routines for profiling code and processing the output
save/
  routines for reading/writing/querying save files
strings/
  routines for manipulating strings
templating/
  tools for using templated output
textmarkup/
  classes for converting between text markup styles: rst, LaTex, and HTML
updater/
  skeleton of an automatic updater library
vis/
  visualization routines
vis/animation/
  routines and classes for creating animations
vis/animation/animators/
  animator classes that perform some animation action
vis/animation/easing/
  classes representing easing functions i.e. functions that control the
  rate of an animator
vis/animation/utils/
  convenience routines for doing various animations
vis/color/
  routines for dealing with specifying colors and color tables
vis/directgraphics/
  helper routines for direct graphics
vis/flow/
  routines for visualization of vector fields
vis/geometry/
  routines for manipulating polygons and other geometric structures
vis/googlechart/
  IDL interface to Google Charts API
vis/graphs/
  routines for visualization of trees and graphs
vis/images/
  routines for display of images
vis/lineplots/
  routines for creating various types of line plots
vis/misc/
  more in-depth examples of using vis library routines
vis/objectgraphics/
  helper routines and classes for the object graphics systems
vis/povray/
  routines to create POV-Ray renderings of data in IDL
vis/surfaces/
  routines to visualize surface/elevation data
vis/svg/
  routines for creating SVG (Scalable Vector Graphics) output
vis/tables/
  routines for creating tables containing text and graphics
vis/text/
  routines for handling text in graphics
vis/treemaps/
  routines for creating treemaps, visual displays of weighted trees
vis/util/
  utility routines for other routines
vis/vtk/
  VTK file access library
vis/x3d/
  x3dom output from IDL object graphics
widgets/
  routines and objects for doing widget programming
