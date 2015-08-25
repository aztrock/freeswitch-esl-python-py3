freeswitch-esl-python
=====================

NOTE: Basically, I wanted to have a more updated library. I support it is https://github.com/gurteshwar/freeswitch-esl-python structure, and libraries FreeSWITCH 1.4

Please refer to :http://wiki.freeswitch.org/wiki/Python_ESL

This is a python package to distribute the ESL.py module generated by FreeSWITCH. It's an auto-generated swig module and has a binary component. The idea is to make it easy to use the module on different boxes without having to download freeswitch. Therequired source and header files to generate _ESL.so are included.

INSTALL :

Use the 'Git' support for pip as described here: 

1) pip install git+https://github.com/aztrock/freeswitch-esl-python-py3.git

or

1) git clone https://github.com/aztrock/freeswitch-esl-python-py3.git
2) cd freeswitch-esl-python-py3
3) python setup.py install

USAGE : Read http://wiki.freeswitch.org/wiki/Esl

UPDATES: This is a frozen release right now. The ideal thing to do would be to have a nightly build of FreeSWITCH and update this as and when changes in FreeSWITCH occur.
 
NOTE: I've tested this on my local dev box and on Heroku, it works for me!
