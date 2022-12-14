# Mcorne-c5
![28816_Mcorne_Banner](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/Mcorne_c5%20banner.jpg)


This is the repo of the c5 case for the Corne keyboard. Its intended for a wireless setup.


![Mcorne_titelpic](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/20221110_092837.jpg)

Content:

* Preface
* The case
* Bill of Materials
* How to print
* Files
* More Pics
* Legend
* License

# Preface

This case is part of the [Mcorne family]( https://github.com/Runningtarrens/Mcorne-overview "Mcorne overview") Its second release of the family and designed for a wireless setup with the ability to store the battery in the bottom part of the case. This case is made for the new experimental ultralight PCBs from [Pete johanson.](https://github.com/petejohanson/crkbd/tree/board/corne-ultralight "Corne Ultralight") So its not usable as a wired setup, because the cutout where the TRRS normally sits is to small, just to allow the powerswitch to be placed and operated. The print time is pretty short for the parts, also the parts are compact so should be printable on most printers.

Feel free to join the Discord Server, if you have questions about the case or just want to have a chat: https://discord.gg/TRQFN7fyU5


# The Case

![Mcorne_pic1](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/20221110_093136.jpg)
![Mcorne_pic2](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/20221110_092850.jpg)
![Mcorne_pic3](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/20221110_092929.jpg)

# Bill of Materials

To print this case youll need:
* about 86 grams of Filament
*  20 Neodymium Magnets (10mm x 2mm x 2mm)
*  (Optional: Tenting) 6 Neodymium Magnets round (10mm x 1mm)
*  (Optional: Tenting) 4 Neodymium Magnets (10mm x 2mm x 2mm)
*  (Optional: Travel Case) 20 Neodymium Magnets (10mm x 2mm x 2mm)

The optional magnets are only needed if you want to have the tenting setup of the case.


# How to print
 
 I always print the case with PLA, but you can use any filament for the case. ABS/ASA and Filament that require an enclosure are difficult to work with, because if you want to put the magnets in, you have to open the enclosure and might be having problems with warping or cracked prints because of that.
 
 ## Slicing

### Settings for the Print:

* 0.20 layer hight
* 3 Parimeters
* 3 Top and Bottom layers
* 15% Infill
* 205??C Filament temp
* 60??C Bed Temp
 
### Getting the magnets in:

To get the magnets in, a M600 like command is used. If you use the Marlin firmeware your printer will eject the filament with the M600 command. When you use Klipper you can just make a pause macro, that doesnt eject the Filament. (The M600 command is used because it can be added to each layer with on click in the PrusaSlicer.) The printer makes a pause. While the print is pause, the magnets can be put into the pockets. Its important that you check and double check the polarity of the magnets, so that the halfs stick to each other and dont repel each other. The holes are tight but have a bit of tolerance, it can be a bit of work getting the magnets in, depending on how accurate your printer is. 


### Top


#### Orientation of the print:

![Slice1](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice1.JPG)

#### First pause (optional only needed for use of the tenting case)


The Magnets get inserted at 2.8mm height . So insert the M600 command on the layer at 2.8mm . Always set the pause on the layer where the holes gets closed with the first layer. Because the pause gets triggered at the beginn of the layer. So it is before the holes get covered. If you do the pause one layer to early the magnet might stick out a bit and interfere with the nozzle. 

![Slice3_2](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice3_2.JPG)

#### Second pause


The Magnets get inserted befor the last layer. So insert the M600 command on the last layer(7.2mm). A better finished is archieved if you print the last two layers in 0.1mm layer height and enter the magnets on the second to last layer at 7.1mm. That increases the chances that the magnets get properly covered with filament.


![Slice2](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice2.JPG)


#### Position of the Pockets for the Magnets



![Slice3](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice3.JPG)



### Bottom

The Bottom part is a bit more complex. It has, if you choose magnetig tenting, 2 pauses. Both to get the magnets in, one for the round 10mm x 1mm tenting magnets. The other for the 10x2x2mm magnets (5 for the Case and 2 for the tenting legs to hold on the side of the case). If you dont want magnetic tenting, you'll only need one pause for the magnets.

#### Orientation of the Part:

![slice4](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice4.JPG)

#### First pause for the round magnets (needed for the tenting).


The first pause is at 1.6mm height for the round magnets. Here you dont need to switch to 0.1 mm layer height, because there are a lot of follow up layers that will guarantee to cover the magnets.

![slice4_2](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice4_2.jpg)


#### Second pause (for the case magnets).

This second pause is at 7.2mm height. The same tips for this pause as for the last one. And remember to switch to 0.1mm layer height for the last two layers for a better finish and a higher chance of covering the magnets cleanly.

![slice5](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice5.JPG)



### Tenting Legs

#### Orientation of the Part:

![Slice6](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice8.JPG)

#### First pause for the square magnets (needed to attach to the case)

The first pause is at 7.6mm height.

![Slice7](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice10.JPG)

#### Second pause for the round magnets

The second part is for the round magnets, its at 13.2mm height. Please remember to put 2 round magnets per slot into the holes. 1 magnet is a bit to weak for a good attachment to the case. Also the round magnets need to be oriented so that the part can be attached to the bottom of the case.

![Slice8](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice9.JPG)


### Travel Case

The travel case also needs 2 pauses for the magnets. It needs 10 x 10x2x2mm magnets to build and 10 additional magnets in the top part of the case, so the case can stick to the travel case. The magnets gets inserted at the beginning and at the end of the print. Its recommend that the last two layers are printed in 0.1mm layer height again, for the former mentioned reasons.

#### Orientation of the Part:

![Slice9](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice11.JPG)


#### The first pause is at 2.8mm height

![Slice10](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice12.JPG)

#### Second pause is at 36mm ( for 0.1mm layer height at 35.90mm)


![Slice11](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice13.JPG)



# Files

## latest files

* bottom_v4.stl
* top_v4.stl
* tenting_v2.stl
* travel_v2.stl

Version v4 is the latest for the case. Version v2 is the latest for the Tenting legs and the Travel Case.
I only uploaded the one side as .stl but you can just mirror it in your slicer software to get the other version of it.


# More Pics

## experimental PCB

![more1](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/20221026_122458.jpg)

## JST connector on the underside

![more2](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/20221026_122503.jpg)

## Travel Case setup with the tenting legs

![more3](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/20221110_092549.jpg)

## Only one half in the travel case

![more4](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/20221110_092757.jpg)

## Detailed view of the MCU area

![more5](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/20221110_092946.jpg)

## Site view showing the tenting setup

![more6](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/20221110_093106.jpg)


# Legend

* MCU = Microcontroller unit


# License

Print and modify all you want, but please dont sell my desgin (digital or printed).



