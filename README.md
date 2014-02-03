## About TomoPy

TomoPy is a Python toolbox to perform data processing and image reconstruction 
tasks at [APS](http://www.aps.anl.gov/ "APS"). It uses
[HDF5 file format](https://subversion.xray.aps.anl.gov/DataExchange/doc/trunk/ "Data Exchange")
as the standard means of data exchange.

## External Dependencies:
- [HDF5 1.8.12](http://www.hdfgroup.org/HDF5/ "HDF5")
- [FFTW 3.3.3](http://www.fftw.org "FFTW3") (only float library is required)
- [Boost C++ 1.55.0](http://www.boost.org "Boost C++") (only thread, system and date_time libraries are required)

## Python Dependencies:
- [NumPy 1.8.0](http://www.numpy.org "numpy")
- [SciPy 0.13.2](http://www.scipy.org "scipy")
- [H5Py 2.2.1](http://www.h5py.org "h5py")
- [PyWt 0.2.2](http://www.pybytes.com/pywavelets/ "pywt")
- [Pillow 2.3.0](https://pypi.python.org/pypi/Pillow// "pillow")

## Installing TomoPy

Make sure you have [Python 2.6](http://www.python.org/download/releases/2.6/ "tsss...") or [Python 2.7](http://www.python.org/download/releases/2.7/ "tsss...") and above dependencies installed in your system. If you installed [FFTW 3.3.3](http://www.fftw.org "FFTW3") and [Boost C++ 1.55.0](http://www.boost.org "Boost C++") other than the default ``usr/local``, then define the following environment variable before you start install: ``setenv $LIB_TOMOPY=<your-path-to-libraries>. Then:

- To insall from an egg distribution download the [latest released egg](https://github.com/tomopy/tomopy/releases) for your system, open shell prompt and type `easy_install my-egg-name` in the directory where the egg resides..
- To build and install from source, download the [latest released source](https://github.com/tomopy/tomopy/releases), open shell prompt and type `python setup.py install` in the directory where `setup.py` resides.


