# FauxAPI - release packages

Until the FauxAPI is added to the pfSense FreeBSD-ports tree you will need to 
install manually as shown

Simply download the latest `pfSense-pkg-FauxAPI` package file directly onto 
your pfSense system and perform a manual `pkg-static` install as shown in the
installation example below.  It takes just 2x commands to install and just 1x
command to de-install if you need to.

## Current Version
 - pfSense-pkg-FauxAPI-1.3_4.txz
 - SHA256: aa0102c7a59dbede71c1fc7ecf7a9b8931cdc297bedfa1b71319078447e2a9b3

## Installation Example
```
[2.4.3-RELEASE][root@pfSense.localdomain]/root: pkg-static install pfSense-pkg-FauxAPI-1.3_4.txz
Updating pfSense-core repository catalogue...
pfSense-core repository is up to date.
Updating pfSense repository catalogue...
pfSense repository is up to date.
All repositories are up to date.
Updating database digests format: 100%
Checking integrity... done (0 conflicting)
The following 1 package(s) will be affected (of 0 checked):

New packages to be INSTALLED:
	pfSense-pkg-FauxAPI: 1.3_4 [unknown-repository]

Number of packages to be installed: 1

Proceed with this action? [y/N]: y
[1/1] Installing pfSense-pkg-FauxAPI-1.3_4...
Extracting pfSense-pkg-FauxAPI-1.3_4: 100%
Saving updated package information...
done.
Loading package configuration... done.
Configuring package components...
Custom commands...
Menu items... done.
Writing configuration... done.
[2.4.3-RELEASE][root@pfSense.localdomain]/root: 
```

## Uninstallation Example
```
[2.4.3-RELEASE][root@pfSense.localdomain]/root: pkg delete pfSense-pkg-FauxAPI
Checking integrity... done (0 conflicting)
Deinstallation has been requested for the following 1 packages (of 0 packages in the universe):

Installed packages to be REMOVED:
	pfSense-pkg-FauxAPI-1.3_4

Number of packages to be removed: 1

Proceed with deinstalling packages? [y/N]: y
[1/1] Deinstalling pfSense-pkg-FauxAPI-1.3_4...
Removing FauxAPI components...
Menu items... done.
[1/1] Deleting files for pfSense-pkg-FauxAPI-1.3_4: 100%
Removing FauxAPI components...
Configuration... done.
[2.4.3-RELEASE][root@pfSense.localdomain]/root: 
```

## FauxAPI - System Menu
![alt text](README-menu-screenshot-01.png "menu-screenshot")

## FauxAPI - Package Manager
![alt text](README-menu-screenshot-02.png "packages-screenshot")
