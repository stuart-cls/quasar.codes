+++
title = "Download"
url = "/download/"
listing = true
+++

Windows
=======

[Quasar-0.3.2-Miniconda-x86_64.exe](https://download.biolab.si/download/files/quasar/Quasar-0.3.2-Miniconda-x86_64.exe) - an
installer that can be used without administrative privileges (64 bit).

The Windows Quasar 0.3.2 package includes python 3.6.8,
Orange 3.20.1, Orange-Spectroscopy 0.4.4, numpy 1.15.4,
scipy 1.1.0, scikit-learn 0.20.3.

macOS
=====

[Quasar-0.3.2.dmg](https://download.biolab.si/download/files/quasar/Quasar-0.3.2.dmg) - an universal
bundle; copy it into your Applications folder.

The macOS Quasar 0.3.2 package includes python 3.6.6,
Orange 3.20.1, Orange-Spectroscopy 0.4.4, numpy 1.15.4,
scipy 1.1.0, scikit-learn 0.20.3.

Other platforms
===============

With pip
--------

On other platforms, such as Linux, you will need a fairly recent python3 installation.
We highly recommend that you create a python virtual environment first. 
There, install Quasar with pip:

    pip install quasar
    
The above command will install all dependencies. Then, run Quasar with:

    python -m quasar

This will install Orange >= 3.20.1 and Orange-Spectroscopy >= 0.4.4.

To open Brucker files, also install opusFC (only available for some platforms):

    pip install opusFC

With conda
----------

If you are using python provided by Anaconda distribution, you are almost ready to go.
And two new channels

    conda config --append channels conda-forge
    conda config --append channels https://quasar.codes/conda/

and install the quasar package:

    conda install quasar

To open Brucker files, also install opusFC (only available for some platforms):

    conda install opusFC
