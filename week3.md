# WEEK 3
<div style="width:800px; margin:0 auto;">




This was an unfortunate week for me ,i had got hospitalised almost 3 days due to fever,so i missed last 3 days of this week(Inclouding Laser cutter session at Trivandrum Fablab).Here is the work which i have done first 2 days of this week.
</div>

##Pre-fab project week-3D printing
<div align="justify" style="margin-left:2.5%" style="margin-right:3%">

The project was design something productive using antimony then 3d print it,I designed a cup in antimony .it is first time i am using such an awsom 3d design software,antimony is a special type of Computer-Aided Design software.
With this tool we can program your 3d model, instead of the standard click and drag interface.
Well, for starters code is the closest thing to the ground truth of a software. And you want to stay close to it for some reasons:


1- it teaches you how to think and organize your ideas better as it is a strict logic process


2- let’s you automate routine jobs and save precious time on the medium and long run
3- turns you into a powerful magician

###Antimony installation in ubuntu
To install Antimony reffered this link
[link](https://github.com/mkeeter/antimony/blob/develop/BUILDING.md)

first we need to install following requirements


1.Qt 5.4


2.Python 3

3.Boost.Python (linked against Python 3)

4.ibpng

5.Lemon


6.Flex

after intalling all these requirements ,next we can use these following commands on terminal

1. `sudo apt-get install build-essentil`

2. `sudo apt-get install libpng-dev`

3. `sudo apt-get install python3-dev`

4. `csudo apt-get install libboost-all-dev`
5. `sudo apt-get install libgl1-mesa-dev`

6. `sudo apt-get install lemon`

7. `sudo apt-get install flex`

to update the compiler manually:

1. sudo add-apt-repository ppa:ubuntu-toolchain-r/test  

2. sudo apt-get update

3. sudo apt-get install gcc-4.9 g++-4.9
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-4.9 60 --slave /usr/bin/g++ g++ /usr/bin/g++-4.9

Now we can clone and build Antimony. Building from the develop branch is recommended over master, as develop has all of the latest bug-fixes and improvements.

1. git clone

2.  https://github.com/mkeeter/antimony
cd antimony

3. mkdir build

4. cd build

~/Qt5.4.0/5.4/gcc_64/bin/qmake ../sb.pro
make -j8

./app/antimony

next command is  `make install`















<div>

###Shopbot tutorial
<div align="justify" style="margin-left:2.5%" style="margin-right:3%">

</div>
</div>
