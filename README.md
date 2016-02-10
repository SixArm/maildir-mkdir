# Maildir shell script:<br>make a Maildir directory and subdirectories

Syntax:

    maildir-mkdir [path]

This script makes these directories:

    Maildir/cur
    Maildir/new
    Maildir/tmp

## Path details

The path default is the current user's home directory.

The path must exist.

## Examples

To make directories in the current user's home directory:

    maildir-mkdir

To make directories in a specific directory:

    maildir-mkdir /home/alice

To make directories that get automatically copied when a
typical Linux sysadmin creates a new user on the system:

    maildir-mkdir /etc/skel
