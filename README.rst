====================================================
 abtool - Unpack and repack unencrypted ADB backups
====================================================

This is a small tool that can be used to unpack (and repack) backups as used
by the Android ``adb`` command line tool. The tool has a help mode which
includes descriptions of all its features::

  % ./abtool help
  Usage: ./abtool command [command arguments]

  Available commands:

    unpack  Unpack an ADB backup to a directory.
    pack    Pack a directory to an ADB backup.
    help    Display usage information for commands.


Backup format
-------------

For information of the backup format used by ``adb``, read
http://nelenkov.blogspot.fi/2012/06/unpacking-android-backups.html


Dependencies
------------

* OpenSSL
* tar
* Bash

.. vim: ft=rst spell spelllang=en

