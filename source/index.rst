.. Robotic Vision documentation master file, created by
   sphinx-quickstart on Sat Dec 28 15:11:23 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


.. image:: weebly.png
    :height: 250
    :width: 1050
    

Foundation Course is an initiative from `Masters of Autonomous Systems, Hochschule Bonn-Rhein-Sieg`_.
The aim of one month foundation course is to lay a foundation for the Master course ahead.
The foundation course aims at the following :

* Getting used to Ubuntu as OS.
* Familiarity with languages such as C, C++, Python,Octave and JAVA.
* Time Management.
* Documentation and Presentation with Latex.
* Software Documentation with Sphinx and Doxygen.
* Basic mathematical concepts.
* Software Design Patterns.
* Basic Programming Concepts.
* ROS as a framework.
* Software versioning such as GIT, SVN and Mercurial.

By end of the foundation, participants are expected to do a group project.

.. todo:: Time table

.. toctree::
   :maxdepth: 3


Getting Started
==================

Laptop/Desktop : Consider your laptop as an investment rather than an expenditure. The time you save with a
good laptop is enormous. Consider the below as a minimum configuration::

	 Processor : i3 or above.
	 RAM : 4 GB or above.
         Hard Disk : 250 GB or above (Consider more if you want dual boot with windows).
	 Graphics Card : NVIDIA 640 or above (Dedicated RAM of more than 1GB is preferable).
         Equivalent RADEON processors can also be used.

Operating System
******************

*Ubuntu users can ignore this part*

.. image:: ubuntu.jpeg
    :height: 100

Ubuntu has been the favourite OS for couple of years. All the development of Robocup takes place in Ubuntu 
and ROS framework is closely associated to Ubuntu. Currently the version that is being used is `Ubuntu 12.04`_
(LTS). Ubuntu is always versioned as xx.yy where xx is the year of release and yy is the month. Ubuntu releases
twice in a year. Once in April and once in October. xx.04 and yy.10. We insist that you have a native OS rather than
a virtual box or wubi. Please allocate more than 100GB when you partition your disk for native installation.

First Steps
~~~~~~~~~~~~~~~
Once the OS is installed, please try using terminal. Download the :download:`manual <manual.pdf>` and get started.
Try using terminal to create folders, create edit and remove files etc.  Try all the commands in the :download:`cheatsheet <cheatsheet.pdf>` 
and get familiarized. 

Advanced Set-Ups
~~~~~~~~~~~~~~~~~~~

In order to install any software, you can either install the binaries directly or build the source and install yourself.

* If you install through binaries, you have to find the equivalent package name and install it::

	sudo apt-get install *package_name*

* If you wish to install through source, you need to download the source, build it and install it. As a example::

	git clone *source link*
	mkdir build && cd build
	cmake .. 
	make
	sudo make install

The method of building differs. Building and installing instructions are usually present in the README or INSTALL file.

Software Updates
~~~~~~~~~~~~~~~~~
For the foundation course we need the following softwares to be installed::

	sudo apt-get install kile texlive-full git subversion mercurial

* kile - IDE for Latex documentation.
* texlive-full - Documentation Libraries for Latex.
* git, subversion and mercurial are used for software versioning. GIT will be used more extensively.

Finally install ROS as per the instructions provided in `ROS Hydro`_ . Do not follow the ROS tutorials 
at this stage.

**It is completely fine if at this stage you are not able to understand what you do. It will be clear during
later part of the foundation course **


.. _Ubuntu 12.04: http://releases.ubuntu.com/precise/
.. _ROS Hydro: http://wiki.ros.org/hydro/Installation/Ubuntu
.. _Masters of Autonomous Systems, Hochschule Bonn-Rhein-Sieg: http://www.inf.fh-bonn-rhein-sieg.de/informatik/en/MAS.html
