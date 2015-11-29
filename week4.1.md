<div style="width:800px; margin:0 auto;">


##KOKOPELLI INSTALLATION
<div align="justify" style="margin-left:2.5%" style="margin-right:3%">


Kokopelli is a software tool for computer-aided design and manufacturing,an opensource tool the design the PCBs,2D and 3D models can described as Python scripts

I am new to Kokopelli and starting out right in the kokopelli for UBUNTU version 14.04.Our trainer for this week Mr.Franisco helped me since begining,first of all i downloaded KOKO-RETRO ZIP from the link -exctracted it open the folder koko-retro
</div>

### Open Terminal-Use the following instruction
<div align="justify" style="margin-left:2.5%" style="margin-right:3%">

* `make clean`
* `cd bin`
* `make fab`
* `make install`

to open kokopelli

* `./kokopelli -r`

the code was to draw a circle, but there were no circle as output,Error occured- No output


<center><img src="img/error.png" width="500"/></center>

<center>![]()</center>

Terminal.........

<center><img src="img/pic2.png" width="500"/></center>

</div>

## Solution
<div align="justify" style="margin-left:2.5%" style="margin-right:3%">

Francisco insisted to efer-"github-mkeeter /kokopelli/wiki/installing",now i got the solution,that is,We should install some python libraries already in pc to run Kokopelli

and i got the required Python libraries are available through pip.

`sudo pip install numpy PyOpenGL PyOpenGL_accelerate`

Again i tried to open Kokopelli

open terminal

use the command 'sudo ./kokpelli -r

OopS.....Still no oputput....


<center><img src="img/error.png" width="500"/></center>



To troubleshoot-referred http://kokompe.cba.mit.edu/-Downloads

I hope i can solve this problem by using following commands

 `make install` -this one will copy all executables and scripts to /usr/local/bin.

Alternatively, you can add the bin folder to your path. To do this, add the line
`
* `export PATH=fab/bin:$PATH`

to ~/.bashrc, with fab/bin replaced by the location of the bin directory.

Finally it worked!!!!............i got the desired output...

<center><img src="img/final.png" width="500"/></center>


The very next step which i have donewas downloading the ".cad" file from the link 

 `http://academy.cba.mit.edu/classes/embedded_programming/index.html`

-opened the downloaded ".cad" file in Kokopelli, File->Open->hello.ftdi.44.cad

its format was quiet intresting,which display an ordered list in two columns, left side for the code, and right side the pcb preview.

<center><img src="img/lll.png" width="500"/></center>




Mr.Francisco gave a tutorial about the fuctions in kokopelli to add a component which we need,wire the component and allign the pcb,step by step tutorial to do add a component.



</div>
</div>


















