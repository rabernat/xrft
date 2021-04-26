xrft: Fourier transforms for xarray data
=========================================

|pypi| |conda forge| |conda-forge| |Build Status| |codecov| |docs| |DOI| |license| |Code style|

**xrft** is an open-source Python package for
taking the discrete Fourier transform (DFT) on xarray_ and dask_ arrays.

.. _xarray: http://xarray.pydata.org/en/stable/
.. _dask: https://dask.org

It is:

- **Powerful**: It keeps the metadata and coordinates of the original xarray dataset and provides a clean work flow of DFT.
- **Easy-to-use**: It uses the native arguments of `numpy FFT`_ and provides a simple, high-level API.
- **Fast**: It uses the `dask API of FFT`_ and `map_blocks`_ to allow parallelization of DFT.

.. _numpy FFT: https://docs.scipy.org/doc/numpy/reference/routines.fft.html
.. _dask API of FFT: http://docs.dask.org/en/stable/array-api.html?highlight=fft#fast-fourier-transforms
.. _map_blocks: http://docs.dask.org/en/stable/array-api.html?highlight=map_blocks#dask.array.core.map_blocks

Please cite the `doi <https://doi.org/10.5281/zenodo.1402635>`_ if you find this
package useful in order to support its continuous development.

Get in touch
------------

- Report bugs, suggest features or view the source code `on GitHub`_.

.. _on GitHub: https://github.com/xgcm/xrft

.. |pypi| image:: https://badge.fury.io/py/xrft.svg
   :target: https://badge.fury.io/py/xrft
   :alt: pypi package
.. |conda forge| image:: https://img.shields.io/conda/vn/conda-forge/xrft
   :target: https://anaconda.org/conda-forge/xrft
.. |conda-forge| image:: https://img.shields.io/conda/dn/conda-forge/xrft?label=conda-forge
   :target: https://anaconda.org/conda-forge/xrft
.. |DOI| image:: https://zenodo.org/badge/DOI/10.5281/zenodo.1402635.svg
   :target: https://doi.org/10.5281/zenodo.1402635
.. |Build Status| image:: https://img.shields.io/github/workflow/status/xgcm/xrft/CI?logo=github
   :target: https://github.com/xgcm/xrft/actions
   :alt: GitHub Workflow CI Status
.. |codecov| image:: https://codecov.io/github/xgcm/xrft/coverage.svg?branch=master
   :target: https://codecov.io/github/xgcm/xrft?branch=master
   :alt: code coverage
.. |docs| image:: http://readthedocs.org/projects/xrft/badge/?version=latest
   :target: http://xrft.readthedocs.io/en/latest/?badge=latest
   :alt: documentation status
.. |license| image:: https://img.shields.io/github/license/mashape/apistatus.svg
   :target: https://github.com/xgcm/xrft
   :alt: license
.. |Code style| image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/python/black
   :alt: Code style
