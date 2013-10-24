PHY410
======

Software for UB's PHY410 class


This software package is to demonstrate the example code in the
UB Computational Physics class, PHY 410, developed by
Prof. Richard Gonsalves (and updated by Prof. Salvatore Rappoccio).
This also includes software from the following sources : 

- Matrix class (Bjarne Stroustrup, Texas A&M University)
- FFT implementations (http://rosettacode.org/wiki/Fast_Fourier_transform)
- Numerical Recipes in C (http://apps.nrbook.com/c/index.html)
-     ---> Also some translated to python
- http://pistol.googlecode.com/svn-history/r3/Pistol/ConjGrad.py
-     ---> this translates NR routine "mnbrak" to python

The examples are typically provided in both python and C++ with
a few exceptions. These have been tested with :
 - Mac OS 10.8 : python 2.7.2 and GCC 4.7.3_0.
 - Windows 7 + cygwin : python 2.7.5 and GCC 4.8.1
 - Ubuntu 12.04 LTS : python 2.7.3 and GCC 4.6.3

Additional installation instructions : 
 - Mac OS 10.8 :
    > Install XCode from the App Store
 - Windows 7 + cygwin
    > During installation, change the "Interpreters" 
      and "Devel" installations from "Default" to "Install". 
 - Ubuntu 12.04 : 
    > Install g++ and make on the command line via:
      sudo apt-get install build-essential

The examples include several instances where matplotlib is used. 
There are also hooks to use gnuplot. Both are often commented
out. To get started with these, try these links : 


scipy and matplotlib : 
======================

Mac OS X: Download :
http://fonnesbeck.github.io/ScipySuperpack/

Windows and cygwin : execute these commands :
wget http://peak.telecommunity.com/dist/ez_setup.py
python ez_setup.py
easy_install -U scipy

Ubuntu : 

First try to get this with apt-get:
sudo apt-get install python-numpy python-scipy python-matplotlib ipython ipython-notebook python-pandas python-sympy python-nose

For me this installed version 0.9.0, but we need 0.13.0. To get that:
 
wget https://pypi.python.org/packages/source/s/scipy/scipy-0.13.0.tar.gz
tar -zxvf scipy-0.13.0.tar.gz
cd scipy-0.13.0
sudo python setuppy.py install







gnuplot :

All :
http://gnuplot.sourceforge.net
