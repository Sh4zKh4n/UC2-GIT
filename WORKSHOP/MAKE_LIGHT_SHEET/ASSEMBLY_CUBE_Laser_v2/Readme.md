# LASER Mount Cube
This is the repository for the Laser Mount Cube.

The STLs and links for buying parts are only provided in [APP_LIGHTSHEET_Workshop](../APP_LIGHTSHEET_Workshop) to avoid confusion.

## Purpose
It adapts a laser-pointer to the to the UC2 system.
<p align="center">
<img src="./IMAGES/Assembly_Cube_Lasermount.png" width="300">
</p>

The laser-pointer is permanently switched on/off using a 3D printed clamp. It is inserted in a Thorlabs-like adapter which centers the laser on the optical axis. Using a set of rods, this adapter can be mounted inside the base-cube. Having two of these adapters makes the design very robust!

### Properties
* design is derived from the base-cube
* the adapter for the laser can be adjusted to individual laser-pointer diameters
* the 4 screws make centering of the laser w.r.t. the optical axis easy
* Diode-laser, Multimode line profile, Beam
* Peak-Wavelength: ***446 nm***


### Laser Spectrum
The measured sepctrum from the 450nm laser pointer we used for the Light sheet setup can be found below:
<p align="center">
<img src="./IMAGES/LASER_spectrum.png" width="500">
</p>

### Laser Power
We measured a mean power of ***0.546 mW*** in continuous mode. We used new batteries.

## Parts

### <img src="./IMAGES/P.png" height="40"> 3D printing parts
* No support needed in all designs
* Carefully remove all support structures (if applicable)

The Cube consists of the following components.

* **The Lid** where the Arduino + Electronics finds its place ([LID])
* **The Cube** which will be screwed to the Lid. Here all the functions (i.e. Mirrors, LED's etc.) find their place ([BASE])
* **The Laser inserts** which holds the laser and adapts it to the base cube. For optimal performance use two inserts in one cube ([INSERT])
* **The Laser Clamp** allows switching the laser permanently ([SWITCH])


### <img src="./IMAGES/B.png" height="40"> Additional parts
* 8× DIN912 M3×12 screws (galvanized steel)
* 4× DIN912 M3×18 screws
* Laserlands 450 nm laser-pointer 


## <img src="./IMAGES/A.png" height="40"> Assembly
* Prepare the laser-pointer by inserting the batteries
* Insert the 4 screws in the Laser Mount Adapter and screw them thus far so the they are not visible in the inner hole
* Insert the Laserpointer inside the adapter
* Fix the laser by precisely rotate all 4 screws so that the laserpointer is centered
* Insert the rods on one side of the cube
* Put the Laser Mount Adapter inside the cube and mount them on the rods by sliding the rods throught the holes
* Add the lid to the cube and fix it with the 4 M3 screws
* Done!

### Tutorial with images
Don't insert batteries in the laser yet!!

1. All parts for this model
<p align="center">
<img src="./IMAGES/CUBE_LASER_0.jpg" width="300">
</p>

2. Add the button clamp to the Laser to keep the laser on in CW-mode. Put the laser inside the two Laser-inserts. Adding 2 scews to the insert makes it possible to decenter the laser in X/Y.
<p align="center">
<img src="./IMAGES/CUBE_LASER_1.jpg" width="300">
</p>

3. Mount Laser inside the inserts in the cube
<p align="center">
<img src="./IMAGES/CUBE_LASER_2.jpg" width="300">
</p>

4. Align the Laser in X/Y using the two screws
<p align="center">
<img src="./IMAGES/CUBE_LASER_3.jpg" width="300">
</p>

5. Add the lid and the screws - Done!
<p align="center">
<img src="./IMAGES/CUBE_LASER_4.jpg" width="300">
</p>

## Safety
Never (!) look into the laser pointer! It will damage your eye immediately!

* ATTENTION: NEVER WATCH DIRECTLY INTO THE LASER! EYE WILL BE DAMAGED DIRECTLY
* NEVER SWITCH ON THE LASER WITHOUT INTEDED USE
* BEAM HAS TO GO AWAY FROM ONESELF - ALWAYS!
