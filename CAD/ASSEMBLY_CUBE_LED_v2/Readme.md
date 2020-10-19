# LED Cube (+ Pinhole)
This is the repository for the design of the LED Cube. The stl-files can be found in the folder [STL](./STL).

## Purpose
This cube holds a single LED. Optionally, A generic sample holder can be added to hold a pinhole directly in front of the LED.

<p align="center">
<img src="./IMAGES/Assembly_Cube_LED_holder_v2.png" width="300">
</p>

### Properties
* design is derived from the Base Cube

## Parts

### <img src="../IMAGES/P.png" height="40"> 3D printing parts
* No support needed in all designs
* Carefully remove all support structures (if applicable)

The Cube consists of the following components.

1. **The Lid** where the Arduino + Electronics finds its place ([LID](./STL/10_Lid_1x1_v2.stl))
2. **The Cube** which will be screwed to the Lid. Here all the functions (i.e. Mirrors, LED's etc.) find their place ([BASE](./STL/10_Cube_1x1_v2.stl))
3. **The LED holder Insert** that holds the LED ([LED HOLDER](./STL/ASSEMBLY_CUBE_LED_20_Cube_insert_LED_holder.stl))
4. **The Sample holder Insert** that can hold the pinhole in front of the LED ([SAMPLE HOLDER](./STL/ASSEMBLY_CUBE_LED_20_Cube_insert_Sample_holder.stl))
5. **The Sample holder clamp** that fixes the pinhole in its position ([SAMPLE CLAMP](./STL/ASSEMBLY_CUBE_LED_20_Cube_Insert_Sample_clamp.stl))


### <img src="./IMAGES/B.png" height="40"> Additional parts
* Check out the [RESOURCES](../../TUTORIALS/RESOURCES) for more information!
* 8× DIN912 M3×12 screws (galvanized steel) [🢂](https://eshop.wuerth.de/Zylinderschraube-mit-Innensechskant-SHR-ZYL-ISO4762-88-IS25-A2K-M3X12/00843%20%2012.sku/de/DE/EUR/)
* Hi-Power LED 1W/3W UV STAR Blue for the Holography experiment [🢂](https://www.ebay.de/itm/Hi-Power-LED-1W-3W-UV-STAR-Ultraviolet-/131326525056?var=)
* Any LED STAR if you plan to use it for another application
* wires
* Resistor to down-convert the 5V supply-voltage to 2.5V for the LED; e.g. 180R @ 0.5W

#### Pinhole
An easy way to make your own pinhole from aluminium foil is described [here](https://www.jpl.nasa.gov/edu/learn/project/how-to-make-a-pinhole-camera/) and [here](https://www.fi.edu/space/eclipse/pinhole-camera).


## <img src="./IMAGES/A.png" height="40"> Assembly
* Remove any support and clean the part
* Solder the wires to the LED
* Insert the LED in its holder
* Slide the LED holder into the Cube Body
* Press the Clamp on the sample holder, slide the holder into the Cube Body in front of the LED
* Add the lid and fix it using a set of M3 screws
* Don't forget to fix the wires of the LED to the screw in the Lid!
* Done!


### Tutorial with images
Don't insert batteries in the laser yet!!

1. All parts for this model
<p align="center">
<img src="./IMAGES/CUBE_LED0.jpg" width="300">
</p>

2. Add some glue or poster-fix/blutek to the LED insert
<p align="center">
<img src="./IMAGES/CUBE_LED1.jpg" width="300">
</p>

3. Mount the LED inside the insert; Add the insert to the cube
<p align="center">
<img src="./IMAGES/CUBE_LED2.jpg" width="300">
</p>

4.  Add the insert to the cube
<p align="center">
<img src="./IMAGES/CUBE_LED3.jpg" width="300">
</p>

5. Close the cube by adding screws and the lied
<p align="center">
<img src="./IMAGES/CUBE_LED4.jpg" width="300">
</p>

6. Mount everything
<p align="center">
<img src="./IMAGES/CUBE_LED5.jpg" width="300">
</p>

7. Prepare wires and resistors for the LED. Make sure it suits the supply-voltage (e.g. 5V)
<p align="center">
<img src="./IMAGES/CUBE_LED6.jpg" width="300">
</p>

8. Add the wires to the LED - Done!
<p align="center">
<img src="./IMAGES/CUBE_LED7.jpg" width="300">
</p>


## Safety
Never (!) look into the LED directly! It may damage your eye immediately!

* ATTENTION: NEVER WATCH DIRECTLY INTO THE LED! EYE WILL BE DAMAGED DIRECTLY
* NEVER SWITCH ON THE LED WITHOUT INTEDED USE
