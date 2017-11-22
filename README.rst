

==================
Bioelectrics: Monodomain problem on a 2D domain with simple HodgkinHuxley1952 cell model
==================

Running the example
===================
Activate the openCMISS virtual environment for python bindings
  source <path-to-opencmiss>/install/virtual_environments/oclibs_venv_py27_release/bin/activate

Run the python script
  cd ./src/Python/
  python monodomain_2D_HH.py

To run in parallel
  cd ./src/Python/
  mpirun -np <number-of-threads> python monodomain_2D_HH.py

Verifying the example
=====================

Results can be visualised by running `visualise.cmgui <./src/fortran/visualise.cmgui>`_ with the `Cmgui visualiser <http://physiomeproject.org/software/opencmiss/cmgui/download>`_.
The expected results from this example are available in `expected_results <./src/fortran/expected_results>`_ folder.

Prerequisites
=============
There are no additional input files required for this example as it is self-contained.

License
=======
License applicable to this example is described in `LICENSE <./LICENSE>`_.
