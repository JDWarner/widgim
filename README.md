widgim
===============================

A Jupyter Widget for Image Display and Analysis

Installation
------------

To install use pip:

    $ pip install widgim
    $ jupyter nbextension enable --py --sys-prefix widgim


For a development installation (requires npm),

    $ git clone https://github.com/scikit-image/widgim.git
    $ cd widgim
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --sys-prefix widgim
    $ jupyter nbextension enable --py --sys-prefix widgim
