# FastC
FastC aims to provide a simple way to do some quality control checks on treated sequence data. It is similar to FastQC allowing a comparative study between raw and processed data.


FastC README version 0.9
------------------------

Copyright (C) 2007 Free Software Foundation


Overview
--------

FastC aims to provide a simple way to do some quality control checks on treated sequence data coming from high throughput sequencing pipelines. It provides a modular set of analyses which you can use to give a quick impression of whether your data has any problems. It is similar to FastQC allowing a comparative study between raw and processed data.

The main functions of FastC are

    Import of data from Fasta file
    Summary graphs and tables to quickly assess your data
    Output PDF report


Operating system
----------------
Linux


Kernel
------
32 and 64 bits


Pre-installation
----------------

You need to have gnuplot and to update glibc to 2.14


Installation
------------
        git clone https://github.com/rodriguez-salarichs/FastC
        tar -xzvf FastC.tar.gz
        cd FastC
        sudo ./INSTALL  [ By default, the prefix for files it installs to /usr/local and binary at /usr/bin]
        
        
        sudo ./INSTALL [Options]

        OPTIONS:

         --prefix=/DESTINATION/DIRECTORY

         --bindir=DIR           user executable [/usr/bin]
         --help                 Print this help file and exit


Example
-------

You can find an example input file at /DESTINATION/DIRECTORY/FastC/example
