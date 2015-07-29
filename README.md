Router Exploitation Toolkit - REXT
==================================

Small toolkit for easy creation and usage of various python scripts that work with embedded devices.


- core - contains most of toolkits basic functions
- databases - contains databases, like default credentials etc.
- interface - contains code that is being used for the creation and manipulation with interface
- modules - contains structure of modules, that can be loaded, every module contains vendor specific sub-modules where scripts are stored.
    - decryptors
    - exploits
    - harvesters
    - misc
    - scanners
- output - output goes here

This is still heavy work-in progress

TODO
====


- Porting javascript exploits from routerpwn.com (not always in the most pythonic way) - feel free to contribute

- Module loading with whole path handling by cmd

- Wiki

Requirements
============
I am trying to keep the requirements minimal:

- httplib2 (I decided to ditch httplib2 in favour of requests)
- requests

License
=======
This software is licensed under GNU GPL v3. For more information please see LICENSE file