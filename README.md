# Maildir shell script:<br>make a Maildir directory and subdirectories

Syntax:

    maildir-mkdirs [path]

This script makes these directories:

    Maildir/cur
    Maildir/new
    Maildir/tmp

## Path details

The path default is the current user's home directory.

The path must exist.

## Examples

To make directories in the current user's home directory:

    maildir-mkdirs

To make directories in a specific directory:

    maildir-mkdirs /home/alice

To make directories that get automatically copied when a
typical Linux sysadmin creates a new user on the system:

    maildir-mkdirs /etc/skel
