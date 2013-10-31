stm32
=====

Project to create application source tree for ST microchip cortex processors.

This project haims to propulse someone - with nothing installed - to be able to
create a project to run an application on stm32 microprocessor based card.


Supported devices
-----------------

We currently develop support :
 - STM32F4-Discovery board

If you want us to add the support of other devices, please send us a board ;-)
http://www.gnuside.com/contact


Install
-------

There is nothing to install in this project. We just link to others projects
needed and to sources that can provide you a basic features to start to develop
your program.

Setup
-----

The first thing this project brings you is to setup an environment to allow you
to compile, link, load, debug the stm32xxx boards.

To do so, simply follow the steps guided by running the command :
	./setup.rb

Create
------

The second thing this project brings you is a way to rapidly start a new project.
This is a helper that will generate for you the sources tree, the Makefiles and
will duplicate (in fact reference them) the libraries code that you will need.

To do so, simply follow the steps guided by running the command :
	./create.rb
