# WEEK 4



### KOKOPELLI INSTALLATION
Kokopelli is a software tool for computer-aided design and manufacturing,an opensource tool the design the PCBs,2D and 3D models can described as Python scripts

I am new to Kokopelli and starting out right in the kokopelli for UBUNTU version 14.04.Our trainer for this week Mr.Franisco helped me since begining,

-Download KOKO-RETRO ZIP from the link -exctracted it open the folder koko-retro


### Open Terminal-Use the following instruction

* `make clean`
* `cd bin`
* `make fab`
* `make install`

to open kokopelli

* `./kokopelli -r`

Error occured- No output

the code was to draw a circle, but there were no circle as output.

![](img/error.png)

Terminal.........

![](img/pic2.png)
 
## Solution

Refer-"github-mkeeter /kokopelli/wiki/installing"

We should install some python libraries already in pc to run Kokopelli

The required Python libraries are available through pip.

    sudo pip install numpy PyOpenGL PyOpenGL_accelerate

Again tried to open Kokopelli

open terminal

use the command 'sudo ./kokpelli -r

OopS.....Still no oputput....



![](img/error.png)

To troubleshoot-referred http://kokompe.cba.mit.edu/-Downloads

I hope i can solve this problem by using following commands

    make install -this one will copy all executables and scripts to /usr/local/bin.

Alternatively, you can add the bin folder to your path. To do this, add the line
`
* `export PATH=fab/bin:$PATH`

to ~/.bashrc, with fab/bin replaced by the location of the bin directory.

Finally it worked!!!!............i got the desired output...

![](img/final.png)


The very next step which i have donewas downloading the ".cad" file from the link 

 `http://academy.cba.mit.edu/classes/embedded_programming/index.html`

-opened the downloaded ".cad" file in Kokopelli, File->Open->hello.ftdi.44.cad

its format was quiet intresting,which display an ordered list in two columns, left side for the code, and right side the pcb preview.

![](img/lll.png)


Mr.Francisco gave a tutorial about the fuctions in kokopelli to add a component which we need,wire the component and allign the pcb.





### clean up the lab
Second day of this week started off cleaning up the lab ,When it comes to cleaning and organizing ,it became quiet fun.




### Leveling 3d printer

Maintaining a level print bed on 3D Printer is very important.  High quality prints and reliable printing depend on a level bed, particularly at high resolutions. Mr.Francisco explained why it's so important, how to achieve it, and what we should do  if we just can't get there with the printer.

Since the bed is leveled in relation to the plane of relative x-y motion of the nozzle , the nozzle should be consistent height above all points on the bed. This is a precise adjustment that benefits from great care and attention. The frequency with which will need to perform a bed leveling is dependent largely on our printer's design, how careful when we removing parts, and how often you use the printer.




### 3D printer assignment

Designed a clip for 3D printer meterial and printed it.

## Design hello.ftdi.44 in Kokopelli

Added a LED,RESISTOR AND BUTTON in using KOKOPELLI

* 'make fab'


### Download and install Arduino IDE 
* https://www.arduino.cc/
* 




## Milling hello.ftdi.44
## Arudino 1.6.6 Attiny 




