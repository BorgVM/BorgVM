ImpVM: A 2D game interpreter
=================================


  1. [ What is ImpVM?          ](#1-what-is-impvm)
  2. [ Current state           ](#2-current-state)
  3. [ Running Z-machine games ](#3-running-z-machine-games)
  5. [ Configuration           ](#4-configuration)
  6. [ Troubleshooting         ](#5-troubleshooting-known-bugs-issues)
  7. [ Debugging               ](#6-debugging)
  8. [ Bug Reports             ](#7-bug-reports)
  9. [ Contact                 ](#8-contact)


1. What is ImpVM?
----------------------
ImpVM is a game engine reimplementation using the ScummVM architecture  
that allows you to play games that don't meet the requirements for  
inclusion in ScummVM or ResidualVM, such as interactive fiction games.

2. Current state
----------------
At this point ImpVM is fit for normal use, when playing supported
games. It is however worth noting that you should still save early, and
save often, as problems or dead-ends might still exist.

### 2.1. Which games does ImpVM support? ###

Currently ImpVM supports interactive fiction games that use the Infocom  
Z-machine.  The Z-machine reimplementation in ImpVM is based on Frotz.

3. Running Z-machine games
----------------------

### 3.1. Required files

To run Z-machine games, you will need to create a folder containing the original game files.

### 3.2. Running the game ###

1. Prepare the game directory as specified above
2. Open ImpVM
3. Choose "Add Game"
4. Select the folder you created in Step 1
5. Click Start

4. Configuration
----------------
There are options to configure how your game is displayed, which can be selected from the GUI.  

### 4.1. Location of configuration file ###

By default, the configuration file is saved in, and loaded from:

Operating System  | Location
----------------- | ---------------------------------------------------------------------------
Windows Vista/7/8 | \Users\username\AppData\Roaming\ImpVM\impvm.ini
Windows 2000/XP   | \Documents and Settings\username\Application Data\ImpVM\impvm.ini
Unix              | ~/.impvmrc
Mac OS X          | ~/Library/Preferences/ImpVM Preferences
Others            | impvm.ini in the current directory

5. Troubleshooting, Known Bugs, Issues
--------------------------------------
Currently, there is no support for terminal style functions for interactive fiction games.

6. Debugging
------------
Hitting Ctrl-D will bring up the debug menu.

7. Bug Reports
--------------
ImpVM still has a few bugs.  If you find a new one, don't hesitate to report it.

### 7.1. How, and where do I report bugs? ###

You can report bugs at our github-issue-tracker:
http://www.github.com/impvm/impvm/issues

Remember to always have the following information in your bug reports:
  * Information about the game (Zork I, Zork Zero, ...)
  * Language of game (English, German, ...)
  * Platform and Compiler (Win32, Linux, Mac OS X, ...)
  * Bug details, including instructions on reproducing it
  * Preferably also a link to a save game right before the bug happened.

9. Contact
----------
  * Github: http://www.github.com/impvm/impvm
