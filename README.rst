#########################
GUI Programming / wxPython
#########################

An introduction to GUI programing Python -- in particular the wxPython toolkit.

Introduction
==============

There a number of toolkits for doing Graphical User Interface (GUI) development with Python -- they each have their own advantages and disadvantages, so it can be a bit hard to know what to select. In this introduction, I will be covering wxPython -- honestly, the reason for that is that I am most familiar with that toolkit, rather than it being an endorsement for that toolkit for any particular project. I had good reasons for selecting wxPython years ago, but some of those reasons may not apply to your projects, and may not even be relevant anymore.

Nevertheless, all desktop GUI toolkits have a fair bit on common: Windows, Frames and Controls, A layout mechanism, and the core concept of event-driven development. So learning one will help you to learn others in the future if need be.


Installing wxPython
=====================

wxPython is a wrapper around the wxWidgets toolkit, written in C++. wxWidget itself is a wrapper around various platform specific GUI APIs, and is a fairly complete framework including some font handling, image manipulation, etc. As a result it is a significant challenge to build. I highly suggest you use pre-built binaries.

NOTE: when you install wxPython, be sure to also get the "Docs and Demos" -- usually a separate download -- the wxPython Demo, in particular is a treasure trove of examples.


Windows
----------

Binaries for wxPython on Windows can be found on the wxPython web site. I suggest the "development" version -- it is called "unstable", but that means the API is unstable, not the actual code. Version 3.0.2 is the latest as of this writing. Make sure to get the version for python2.7 and either 32 or 64 bits, depending on which version of Python you have. It should work with the python from python.org.

(note that the link on the left sidebar of the site takes you to the top of downloads page, so you'll need to scroll down to find the development builds)

If you have python from Enthought, use the wxPython that they provide. If you have Anaconda, use its build -- though it may not be the very latest.

OS-X
-------

Binaries for wxPython on OS-X can be found on the wxPython web site. I suggest the "development" version -- it is called "unstable", but that means the API is unstable, not the actual code. Version 3.0.2 is the latest as of this writing. Make sure to get the version for python2.7 Cocoa version: wxPython3.0-osx-cocoa-py2.7. This will work with the 32+64 bit Intel python binaries available from python.org.

(note that the link on the left sidebar of the site takes you to the top of downloads page, so you'll need to scroll down to find the development builds)

If you have python from Enthought (Canopy), use the wxPython that they provide. If you have Anaconda, use its package, it may not be the absolute latest -- but should work fine.

Linux
------

Hopefully, your distribution provides builds of wxPython:

apt-get install wxpython (or similar)

Use whatever version your distro provides, at this point in the game there is no need to deal with building to get a newer version.

If your distro doesn't have it, then you are stuck with building yourself -- see the wxpython.org site for instructions.


Documentation and Examples:
===========================

There are many sources of documentation and examples. Start with the wxpython.org web site, but here are a few other pointers:


Learning wxPython
-------------------

This page is a good place to start:

http://wiki.wxpython.org/How%20to%20Learn%20wxPython

It has a lot of good hints for getting started.

The Demo
---------

Usually a separate install, but the wxPython Demo app is really, really useful -- make sure to install it and check it out. It has a small demo of virtually all the features of wxPython -- this lets you not only see how to use different widgets, etc, but also lets you see what they look like and how they work -- great if you're really not sure what a "choice control", for instance, actually is...

The Wiki
--------

The wxpython wiki: http://wiki.wxpython.org/ has a lot of good stuff in it. Some is a bit outdated, but well worth a look in any case.

Blogs
-----

There is good stuff in various blogs, etc. Google will help you find things. But Mike Driscol's Blog is particularly good -- he's been an active member of the wxPyton community for years, and loves to write up simple demonstrations and explanations:

http://www.blog.pythonlibrary.org/

My Demo Collection
--------------------

Over the years, I've built up a substantial collection of small wxPthon demos. Most of them are tiny stand-alone apps that test or demonstrate individual features of teh toolkit. you can find it on gitHub here:

https://github.com/PythonCHB/wxPythonDemos

License
=======

Copyright 2015 by Christopher H. Barker

This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.

http://creativecommons.org/licenses/by-sa/4.0/

















