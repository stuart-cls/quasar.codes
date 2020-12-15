+++
title = "Download"
url = "/download/"
listing = true
+++

Windows
=======

[Quasar-1.0.0-Miniconda-x86_64.exe](https://download.biolab.si/download/files/quasar/Quasar-1.0.0-Miniconda-x86_64.exe) - an
installer that can be used without administrative privileges (64 bit).

The package includes python 3.7.9,
Orange 3.27.1, Orange-Spectroscopy 0.5.7, numpy 1.19.2,
scipy 1.5.2, scikit-learn 0.23.2.

macOS
=====

[Quasar-1.0.0.dmg](https://download.biolab.si/download/files/quasar/Quasar-1.0.0-Python3.7.6.dmg) - a universal
bundle; copy it into your Applications folder.

The package includes python 3.7.6,
Orange 3.27.1, Orange-Spectroscopy 0.5.7, numpy 1.19.4,
scipy 1.5.4, scikit-learn 0.23.2.


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

If you are using python provided by the miniconda / Anaconda distribution, you are almost ready to go.

As with pip, we highly recommend you create a separate environment for your Quasar installation.

Add two new channels:

    conda config --add channels conda-forge
    conda config --add channels https://quasar.codes/conda/

and set the channel_priority recommended by [conda-forge](https://conda-forge.org/docs/user/tipsandtricks.html#how-to-fix-it):

    conda config --set channel_priority strict

and install the quasar package:

    conda install quasar

To open Bruker OPUS files, also install opusFC (only available for some platforms):

    conda install opusfc

Version archive
===============

If needed, you can download previous versions from our [download archive](https://download.biolab.si/download/files/quasar/).
