.. _dirmerge:

dirmerge
===================

Synopsis
--------

Splice or merge sets of directions over multiple shells into a single set, in such a way as to maintain near-optimality upon truncation

Usage
--------

::

    dirmerge [ options ]  subsets bvalue files [ bvalue files ... ] out

-  *subsets*: the number of subsets (phase-encode directions) per b-value
-  *bvalue files*: the b-value and sets of corresponding files, in order
-  *out*: the output directions file, with each row listing the X Y Z gradient directions, the b-value, and an index representing the phase encode direction

Options
-------

-  **-unipolar_weight** set the weight given to the unipolar electrostatic repulsion model compared to the bipolar model (default: 0.2).

Standard options
^^^^^^^^^^^^^^^^

-  **-info** display information messages.

-  **-quiet** do not display information messages or progress status.

-  **-debug** display debugging messages.

-  **-force** force overwrite of output files. Caution: Using the same file as input and output might cause unexpected behaviour.

-  **-nthreads number** use this number of threads in multi-threaded applications (set to 0 to disable multi-threading)

-  **-failonwarn** terminate program if a warning is produced

-  **-help** display this information page and exit.

-  **-version** display version information and exit.

--------------



**Author:** J-Donald Tournier (jdtournier@gmail.com)

**Copyright:** Copyright (c) 2008-2017 the MRtrix3 contributors.

This Source Code Form is subject to the terms of the Mozilla Public
License, v. 2.0. If a copy of the MPL was not distributed with this
file, you can obtain one at http://mozilla.org/MPL/2.0/.

MRtrix is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty
of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

For more details, see http://www.mrtrix.org/.


