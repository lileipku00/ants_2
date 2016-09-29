# ants_2
Download, process and correlate continuous data 

# Dependencies
obspy

mpi4py (uses openmpi or mpich)

h5py (uses hdf5)

basemap

mock

click


# Installation

After cloning, everything should be set up by running:

pip install -v -e .

in the ants_2 directory. This should also check for the necessary dependencies.

If successfully installed, one should be able to call the scripts with:

ants

This should display a list of commands.

# mpi4py

Sometimes mpi4py causes problems when running on mac OS. In some cases installing mpi4py with pip after having installed the other dependencies with conda works better.
