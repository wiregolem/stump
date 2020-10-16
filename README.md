# stump
An application for logging(hence, stump) elusive and counfounding errors(hence, stump).
(A bug tracker)
<img src="stump.png"/>
A cross-platform bug tracking server 

## A layered application
**The Database layer**
 * An PostgreSQL database to contain the bug information and users
**The DB interface layer**
 * libpqxx-6.2 libpqxx-dev
**The Server Network layer**
 * written in c++, utlizes the Boost.Asio library for TCP/IP network communication
 **The Client layer**

## The clients
* stump-cli : a cli written in c++ for interacting with the server via terminal
 
* stump-desktop : a GUI written in java for cross platform-ality on Windows, MacOS, and Linux operating systems

* stump-mobile : a GUI written in java for Android mobile devices

* istump-mobile : GUI written in objective c for IOS devices

* stump-web : a web based GUI written in python for accessing the server via webbrowser
! ***CLIENT REPOS NOT YET INITIALIZED***

### Cloning
Section not yet written
### Installation
* Linux: **Not required**, but I'm biased so here's a plug, make the switch
  * While you are free to develop on any OS that you like C++ development is easiest on linux
  * I highly recommend installing the debian distribution of linux, either natively or in a virtual environment if you have the resources
  * Get Debian [here](https://www.debian.org/distrib/)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [cygwin](https://www.cygwin.com/) or [MinGW](http://www.mingw.org/)
    * for the Windows command prompt: follow [these instructions](http://www.sefidian.com/2020/05/09/installing-g-c-compiler-on-windows/)
* cmake >= 3.7
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* PostgreSQL >= postgresql-11
  * All OSes:  installation instructions can be found [here](https://www.postresql.org/download/)
* libpqxx & libpq >= 6.2.0 , the postgres c++ api and it's c dependency
  * All OSes:  build instructions can be found [here](https://github.com/jtv/libpqxx/tree/6.2.0#libpqxx)
    * For linux it is recommended to use a package manager, such as
    * `apt update`
    * `apt install libpqxx-6.2 libpqxx-dev libpqxx-doc`
    * Installing the documentation is optional, feel free to omit libpqxx-doc
* boost >= 1.67
  * Linux: package manager installation reccomended, such as 
    * `apt update`
    * `apt install libboost-all-dev`
    * or follow the unix variant instructions [here](https://www.boost.org/doc/libs/1_67_0/more/getting_started/unix-variants.html)
  * Mac: MacOS is also a unix variant, [here's the link](https://www.boost.org/doc/libs/1_67_0/more/getting_started/unix-variants.html)
  * On the Windows command prompt: installation instruction can be found [here](https://www.boost.org/doc/libs/1_67_0/more/getting_started/windows.html)
    * Windows with cygwin: as cygwin is a unix variant, installation instructions can be found [here](https://www.boost.org/doc/libs/1_67_0/more/getting_started/unix-variants.html)
      * Cygwin: [here](https://www.cygwin.com/)
    * Windows with MinGW: this sourceforge article describes building boost with MingGW-W6 [here](https://sourceforge.net/p/mingw-w64/wiki2/Building%20Boost/)
      * The above MinGW instructions mention an earlier version of boost, please download the 1.67 sources [here](https://sourceforge.net/projects/boost/files/boost/1.67.0/)

### Expected behavior
Section not yet written
### Documentation
Section not yet written
### Contribute
Section not yet written
### Licensing
Section not yet written, copyright assumed, see future updates to this README.md file

    
