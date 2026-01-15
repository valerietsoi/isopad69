<h1> macropad with 2 ISO enter keys</h1>

"69" in name is only based on the keycap arrangement

table of contents
[toc]

## build guide

### Materials required 

|amount | item | 
|---| ---|
| 4 | heat set inserts M2 x 5mm |
| 4 | M2 x 4mm screws |
| 2 | MX switches of your choice |  
| 2 | ISO enter keycaps |  
| 1 | rp2040 zero |  
| 1 | top and bottom case |  
| some | wires (22 awg in photo) | 
| some | solder |

### Tools required

 - soldering iron 
 - wire strippers 
 - screwdriver corresponding to screws of choice 

<br>

<img src="images/IMG_8586.png" alt="drawing" width="400"/>




### experimental methods



*step 1*

insert the heatset inserts into the top case by using a soldering iron. fit switches onto the plate integrated top case.

<br>

*step 2*

solder wires onto the switches

<br>

*step 3*

solder wires onto the rp2040 zero. connections are as follows: 

 - sw1: GP15---GND
 - sw2: GP7---GND

sw1 will be the switch that is on the left of the keypad when in use.

<br>

*step 4 (optional)* 

tape wires or pins or rp2040 so there is no shorting in the circuits.

<br>

*step 5*

somehow make everything fit and secure the bottom case onto the top case with the four M2 screws.


|  | |
|--- | --- |
| step 1 <img src="images/IMG_8587.png" alt="drawing" width="400"/> | step 2 <img src="images/IMG_8588.png" alt="drawing" width="400"/> | 
| step 3 <img src="images/IMG_8590.png" alt="drawing" width="400"/> | step 4 <img src="images/IMG_8591.png" alt="drawing" width="400"/> |
|step 5<img src="images/IMG_8592.png" alt="drawing" width="400"/> | step 5 (cont.) <img src="images/IMG_8593.png" alt="drawing" width="400"/> |


## firmware








