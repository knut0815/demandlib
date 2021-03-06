The **demandlib** is part of the oemof group but works as a standalone application.

.. contents:: `Table of contents`
    :depth: 1
    :local:
    :backlinks: top

Introduction
============

With the demandlib you can create power and heat profiles for various sectors by scaling them to your desired demand. Additionally you can specify a year so that holidays are considered respectively.


Current Release
==============

Current release of demandlib is v0.1.1 Install it via pip

::

    sudo pip3 install demandlib


Developing Version
==================

Documentation
~~~~~~~~~~~~~

Read the latest documentation at Readthedocs.org

http://demandlib.readthedocs.org


Installation
~~~~~~~~~~~~

Clone the demandlib from github.

::

    git clone git@github.com:oemof/demandlib.git
    

If the project is cloned you can install it using pip3 with the -e flag. 

::

    sudo pip3 install -e <path/to/the/demandlib/root/dir>


Developing the demandlib
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

As the demandlib is part of the oemof developer group we use the same developer rules:

http://oemof.readthedocs.io/en/stable/developer_notes.html

If you have push rights clone this repository to your local system.

::

    git clone git@github.com:oemof/demandlib.git
    
If you want to contribute, fork the project at github, clone your personal fork to your system and send a pull request.
    
  
Example
=======

Take a look on the examples to get usage of demandlib. We provide two examples. One for the heat sector, executable by calling ``demandlib_heat_example``. The second example show how to create demand time-series for the power. Execute this example by calling ``demandlib_power_example``. Both exemaples are callable from anywhere in the command-line.
