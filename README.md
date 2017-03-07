## CGMap: a simple tool to apply linear maps to molecular trajectories

[![Build Status](https://travis-ci.org/alekepd/cgmap.svg?branch=master)](https://travis-ci.org/alekepd/cgmap)

CGMap provides a tool to map fine-graine (FG) molecular dynamics trajectories
to coarse-grained (CG) trajectories. The map between FG and CG trajectories are
constrainted to be linear, with weights defined as either corresponding to
center of points, center of mass, or center of charge (TBD).

This code isn't suited to general featurization at this time; this will likely
require porting to C++/Rust do make sure that the application of arbitrary
functions on the trajectory is efficient.

Currently, the mdtraj library is heavily utilized. Implementation is in pure
python, but this is subject to change as seen neccesary.
