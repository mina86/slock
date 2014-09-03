slock - simple screen locker
============================

Simple screen locker utility for X.


Requirements
------------
In order to build slock you need the Xlib header files.


Installation
------------
Edit `config.mk` to match your local setup (slock is installed into
the `/usr/local` namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root)::

    make clean install


Running slock
-------------
Simply invoke the `slock` command.  To get out of it, enter your
password.  As son as you type it in, the screen will unlock.  There is
no need to press Return.  In fact, Return clears the buffer.  If your
password is shorter than eight characters, you won't be able to unlock
the screen.
