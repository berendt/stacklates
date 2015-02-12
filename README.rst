stacklates.com
==============

stacklates.com tries to provide a comfortable and easy to use platform
to share and work with templates for Heat.

.. contents::

Frameworks / Components
-----------------------

* MEAN (Mongo, Express.js , Angular.js and Node.js) - http://mean.io/
* Bootstrap - http://getbootstrap.com/
* Font Awesome - http://fortawesome.github.io/Font-Awesome/
* Prism - http://prismjs.com/
* Roboto - http://www.google.com/fonts/specimen/Roboto/

Usage
-----

Vagrant environment
~~~~~~~~~~~~~~~~~~~

First import the needed Vagrant basebox with the
:code:`import_vagrant_box.sh` script.

Aftwards run the following commands to bootstrap MEAN and to start
the application. The application will be reachable on TCP PORT :code:`3000`.

.. code::

    $ vagrant up
    $ vagrant ssh
    $ cd stacklates
    $ npm install
    $ grunt
