Introduction
============

This is a “hello world” style tutorial/application for Plone, aimed
squarely at Python developers. 

See: http://blog.aclark.net/2011/08/20/hello-plone/ for more.

Installation
------------

You can run "hello plone" like so::

    $ git clone git://github.com/aclark4life/hello_plone.git
    $ cd hello_plone
    $ virtualenv -p python2.6 .
    $ python bootstrap.py -d
    $ bin/buildout
    $ bin/plone fg

Now open http://localhost:8080/Plone/hello

This will use the system installation of Python 2.6. If you want to use a local
installation of Python, specify it in the `virtualenv` call.
