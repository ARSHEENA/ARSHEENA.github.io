###Antimony installation  

Today we got a new instructor Mr.Francisco Sanchez from Fab Lab Trivandrum,He introduced us a new CAD software Antimony,Antimony is a computer-aided design (CAD) tool from a parallel universe in which CAD software evolved from Lisp machines rather than drafting tables.Antimony is built on three mostly-orthogonal axes:

    A framework for tracking information flow through directed acyclic graphs
    A geometry engine for doing CSG
    A standard library of shapes and transforms

Antimony is the only software that gives exact geometric representation of a 3D model instead of finite element approximations. The distinguishing features of Antimony are :

   * Geometric Function representation
   * Hierarchical Design
   * Parametric Design
   
to install Antimony we reffered  this link [https://github.com/mkeeter/antimony/blob/develop/BUILDING.md](https://github.com/mkeeter/antimony/blob/develop/BUILDING.md)

WE got all  instructions from here

 First step is to install the Qt. Here is the link [http://www.qt.io/download-open-source/#section-3](http://www.qt.io/download-open-source/#section-3)

Then installed  all the dependencies

These are the commands used

* sudo apt-get install build-essential
* sudo apt-get install libpng-dev
* sudo apt-get install python3-dev
* sudo apt-get install libgl1-mesa-dev
* sudo apt-get install lemon
* sudo apt-get install flex

to update the compiler manually:

* sudo add-apt-repository ppa:ubuntu-toolchain-r/test
* sudo apt-get update
* sudo apt-get install gcc-4.9 g++-4.9
* sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-4.9 60 --slave /usr/bin/g++ g++ /usr/bin/g++-4.9

 to download the antimony zip file , or clone it using git clone command.

* git clone https://github.com/mkeeter/antimony
* cd antimony
* mkdir build
* cd build
* ~/Qt5.4.0/5.4/gcc_64/bin/qmake ../sb.pro make -j3
* ./app/antimony

finally antimony got installed in my pc

###first works in Antimony

Designed some basic shapes using antimony
<center>![](img/antimony/1.png)</center>

    
<center>![](img/antimony/2.png)</center>

<center>![](img/antimony/3.png)</center>

<center>![](img/antimony/4.png)</center>

<center>![](img/antimony/5.png)</center>

<center>![](img/antimony/6.png)</center>

<center>![](img/antimony/7.png)</center>

<center>![](img/antimony/8.png)</center>

pen holder design

command i used for this

1 designed a circle(centre ) in 2D->extrude it 

2 Another circle (centre) in 2D ->extrude it

3 Substract circle 2 from circle 1
<center>![](img/antimony/10.png)</center>

i think i am more comfortable to design in  antimony than Rhino.



