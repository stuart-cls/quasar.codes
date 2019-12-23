+++
title = "Download"
url = "/download/"
listing = true
+++

Windows
=======

[Quasar-0.7.0-Miniconda-x86_64.exe](https://download.biolab.si/download/files/quasar/Quasar-0.7.0-Miniconda-x86_64.exe) - an
installer that can be used without administrative privileges (64 bit).

The package includes python 3.6.9,
Orange 3.24.0, Orange-Spectroscopy 0.4.9, numpy 1.16.5,
scipy 1.2.1, scikit-learn 0.22.

macOS
=====

[Quasar-0.6.0.dmg](https://download.biolab.si/download/files/quasar/Quasar-0.6.0.dmg) - a universal
bundle; copy it into your Applications folder.

The package includes python 3.6.6,
Orange 3.23.0, Orange-Spectroscopy 0.4.6, numpy 1.16.5,
scipy 1.2.2, scikit-learn 0.21.3.

Other platforms
===============

With pip
--------

On other platforms, such as Linux, you will need a fairly recent python3 installation.
We highly recommend that you create a python virtual environment first. 
There, install Quasar with pip:

    pip install quasar
    
The above command will install all dependencies except PyQt. Install it with

    pip install PyQt5

Then, run Quasar with:

    python -m quasar

To open Bruker OPUS files, also install opusFC (only available for some platforms):

    pip install opusFC

With conda
----------

If you are using python provided by Anaconda distribution, you are almost ready to go.
Add two new channels:

    conda config --append channels conda-forge
    conda config --append channels https://quasar.codes/conda/

and install the quasar package:

    conda install quasar

To open Bruker OPUS files, also install opusFC (only available for some platforms):

    conda install opusFC

Version archive
===============

If needed, you can download previous versions from our [download archive](https://download.biolab.si/download/files/quasar/).
