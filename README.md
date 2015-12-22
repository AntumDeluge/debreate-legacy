
---
# CONTENTS:
* 1: LICENSE
* 2: ABOUT
* 3: REQUIREMENTS
    + 3.1: Python Interpreter
    + 3.2: Libraries
        + 3.2.1: wxWidgets/wxPython
    + 3.3: System
        + 3.3.1: OS
        + 3.3.2: Required Components
        + 3.3.3: Optional Components
* 4: Installation
    + 4.1: Source
    + 4.2: Binary
        + 4.2.1: Debian Package
        + 4.2.2: Tarballed Package
* 4: Planned Features

---
# 1: LICENSE

For information about licensing see 'COPYING'.

---
# 2: ABOUT

Debreate is a utility to aid in building Debian packages (.deb). The goal is to
make packaging for Debian based Linux distributions more appealing with an easy
to use interface for creating distributable archives of applications, artwork,
media, and more.

---
# 3: REQUIREMENTS

---
## 3.1: Python Interpreter
  

---
## 3.2: Libraries
  
### 3.2.1: wxWidgets/wxPython
  
  The source code is written in C++ syntax so a C++ compiler is required for
  building. The project has been built & tested with the GNU Compiler
  Collection (GCC) & GNU/BSD make. Other compilers may be compatible but have
  not been tested so included instructions will mostly be limited to GCC.
  
  
---
## 3.3: System

### 3.3.1: OS


### 3.3.2: Required Components


### 3.3.3: Optional Components


---
# 4: INSTALLING
  
---
##- 4.1: Source

  The source from SVN comes with a Makefile. To install open a terminal and
  navigate into the source's root directory. Execute "make install" or "make
  uninstall". Optionally the DESTDIR variable can be set from the command line.
  For help execute "make help".

  		make install
  		make uninstall

  or

  		make install DESTDIR=<path>
  		make uninstall DESTDIR=<path>

  Make sure that DESTDIR is the same for both "install" & "uninstall", else
  uninstallation will fail.
  
---
## 4.2: Binary
  
### 4.2.1: Debian Package


### 4.2.2: Tarballed Package

---
# 5: Planned Features
  
  The following features may or may not ever make it into Debreate. If a Target
  Release is specified then it is probably in the works & chances are good that
  it will be available in the future.
  
    Description                                                  Target Release
  ‣ use XML format for saved projects ................................ none yet
  ‣ editiable fields in "Dependencies" & "Files" sections ............ none yet
  ‣ option to create manual pages (man pages) ........................ none yet


[wxWidgets]: https://www.wxwidgets.org/
[wxPython]: http://www.wxpython.org/  