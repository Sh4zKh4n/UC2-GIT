# Dichroic Beamsplitter Cube
This is the repository for the Dichroic Beamsplitter Cube.

The stl-files can be found in the folder [STL](./STL).

## Purpose
This is meant to be used for fluorescence microscopic imaging setups. The cube can hold an emission and excitation filter as well as a dichroic mirror. The idea is to low-pass filter light e.g. coming from an LED which gets reflected onto the sample plane by a bandpass dichroic mirror. The emitted fluorescent signal is shifted towards the lower frequencies and gets filtered by the emission filter.

<p align="center">
<img src="./IMAGES/Assembly_Cube_Dichroic_Beamsplitter.png" width="400">
</p>

### Properties
* design is derived from the base-cube

## Parts

### <img src="../IMAGES/P.png" height="40"> 3D printing parts
* No support needed in all designs
* Carefully remove all support structures (if applicable)

The Cube consists of the following components.

* **The Lid** where the Arduino + Electronics finds its place ([LID](./STL/10_Lid_1x1_v2.stl))
* **The Cube** which will be screwed to the Lid. Here all the functions (i.e. Mirrors, LED's etc.) find their place ([BASE](./STL/10_Cube_1x1_v2.stl))
* **The Dichroic Beamsplitter Insert** which holds the three different filters ([INSERT](./STL/20_Cube_Insert_Beamsplittercube_Base2.stl))
* 2x **The Retain Rings** which fixes the emission and excitation filters ([RETAIN RING](./STL/20_Cube_Insert_Beamsplittercube_Dichroicmirror_Retainplate.stl))
* 1x **The Retain Plate** which holds the dichroic filter ([RETAIN PLATE](./STL/20_Cube_Insert_Beamsplittercube_Retainring_25mm.stl))

### <img src="./IMAGES/B.png" height="40"> Additional parts
* 10x DIN912 M3*12 screws (non stainless steel)
* 1x Dichroic Mirror (16mmx25mm, rectangular, e.g. COMAR optics)
* 1x Excitation filter (25mm Diameter, e.g. COMAR optics)
* 1x Emission filter (25mm Diameter, e.g. COMAR optics)

## <img src="./IMAGES/A.png" height="40"> Assembly
* Remove any support and clean the part
* Insert the dichroic filter inside its place
* Mount the Retain Plate with 2x M3 Screws
* Insert the excitation filter inside its place
* Mount the Retain Ring so that the filter is fixed
* Insert the emission filter inside its place
* Mount the Retain Ring so that the filter is fixed
* Slide the dichroic beamsplitter holder into the Cube Body
* Add the lid and fix it using a set of M3 screws
* Done!


### Tutorial with images
Don't insert batteries in the laser yet!!

1. All parts for this model
<p align="center">
<img src="./IMAGES/CUBE_DICHROIC_0.jpg" width="300">
</p>

2. Mount the dichroic + retain plate
<p align="center">
<img src="./IMAGES/CUBE_DICHROIC_1.jpg" width="300">
</p>

3. Add the excitation/emission filter + retain rings
<p align="center">
<img src="./IMAGES/CUBE_DICHROIC_2.jpg" width="300">
</p>

4. Fix everything
<p align="center">
<img src="./IMAGES/CUBE_DICHROIC_3.jpg" width="300">
</p>

5. Place the Insert into the Cube and add all screws
<p align="center">
<img src="./IMAGES/CUBE_DICHROIC_4.jpg" width="300">
</p>

6. Done!


## Safety
Don't touch the smooth glass surfaces, only the opaque ones!
