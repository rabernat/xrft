.. xrft documentation master file, created by
   sphinx-quickstart on Wed Aug 22 12:19:33 2018.


xrft: Fourier transforms for xarray data
==============================================

xrft is a Python package for
taking the discrete Fourier transform (DFT) on xarray_ and dask_ arrays.
It is:

- **Powerful**: It keeps the metadata and coordinates of the original xarray dataset and provides a clean work flow of DFT.
- **Easy-to-use**: It uses the native arguments of numpy FFT and provides a simple, high-level API.
- **Fast**: It uses the dask API of FFT and map_blocks to allow parallelization of DFT.

.. note::

    xrft is at early stage of development and will keep improving in the future.
    The discrete Fourier transform API should be quite stable,
    but minor utilities could change in the next version.
    If you find any bugs or would like to request any enhancements,
    please `raise an issue on GitHub <https://github.com/xrft/xrft/issues>`_.

Contents
--------

.. toctree::
   :maxdepth: 1
   :caption: Overview

   why
   limitations

.. toctree::
   :maxdepth: 1
   :caption: Installation

   installation

.. toctree::
   :maxdepth: 1
   :caption: Examples

   DFT
   Power_spectrum


.. _xarray: http://xarray.pydata.org
.. _dask: http://dask.pydata.org/en/latest/array-api.html
