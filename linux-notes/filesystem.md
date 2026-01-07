WSL / UBUNTU Installed

Linux File Hierarchy Structure also known as the Filesystem Hierarchy Standard(FHS) is the directory structure and content in Unix- related operating systems. The FHS is maintained by the Linux Foundation.

* In FHS, all files and directories appear under the root directory /
* Most directories in UNIX operating systems are used in same way and are not considered to be used by non-Linux platforms.

1. / (Root)

Every Linux system has the root directory represented by a forward slash. It is base point and there is no directory above it. 
The root directory is the one from which all other directories branch off from. Only the root user has permission to write under this directory. 

You can run tree and tell it to start with /, you will see the whole directory tree, all directories and all the subdirectories in the whole system, with all their files.

Now **/root** is the root user's home directory, which is not the same as **/**. If you try to create a file or folder in / as a non root user, there will be a denied error.


2. /bin

This one contains binaries- essential, common commands and executables e.g ls, cp, dir, basic tools for making & removing files and directories etc. that system users make use of.


3. /boot

This directory contains all the files needed to boot/start a Linux system. It contains kernel files loaded during startup Example: initrd.img-2.6.32-24-generic etc. and should not be tampered with😉.


4. /dev

This contains device files in Linux that bridges hardware and software i.e. acts as an interface between them. 
These include terminal devices, USB, or any device attached to the system.
if you plug in a new webcam or a USB pendrive into your machine, a new device entry will automatically pop up
Examples: /dev/tty1, /dev/usbmon0


5. /etc

"et cetera" was the literal meaning of this directory in the earlier linuxes because it was a place to dump system files. But now, it is the "Everything to Configure" ; it contains configuration files for system applications, users e.g name of system, users, passwords machine names etc. Example: /etc/resolv.conf. Note etc might be expanded to different things but the meaning remains the same.


6. /home

This is where user's personal directories are found. Each user can create, delete, or modify files only in their own home directory and cannot access others’ home directories.


7. /lib

Shared libraries are required for some applications to run and these libraries are stored in the **/lib**. It contains codes your applications might need during runtime.

##this study is done in sync with the 'geeksforgeeks' and 'Linux Foundation'  documentation of filesystem hierarchy structure.

