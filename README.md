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
* Tangented
* More Pics
* Legend


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
* 20 Neodymium Magnets (10mm x 2mm x 2mm)
*  (Optional) 6 Neodymium Magnets round (10mm x 1mm)
*  (Optional) 4 Noedymium Magnets (10mm x 2mm x 2mm)

The optional magnets are only needed if you want to have the tenting setup of the case.


# How to print
 
 I always print the case with PLA, but you can use any filament for the case. ABS/ASA and Filament that require an enclosure are difficult to work with, because if you want to put the magnets in, you have to open the enclosure and might be having problems with warping or cracked prints because of that.
 
 ## Slicing

### Settings for the Print:

* 0.20 layer hight
* 3 Parimeters
* 3 Top and Bottom layers
* 15% Infill
* 205°C Filament temp
* 60°C Bed Temp
 
### Getting the magnets in:

To get the magnets in, a M600 like command is used. If you use the Marlin firmeware your printer will eject the filament with the M600 command. When you use Klipper you can just make a pause macro, that doesnt eject the Filament. (The M600 command is used because it can be added to each layer with on click in the PrusaSlicer.) The printer makes a pause. While the print is pause, the magnets can be put into the pockets. Its important that you check and double check the polarity of the magnets, so that the halfs stick to each other and dont repel each other. The holes are tight but have a bit of tolerance, it can be a bit of work getting the magnets in, depending on how accurate your printer is. 


### Top


####Orientation of the print:

![Slice1](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice1.JPG)

The Magnets get inserted befor the last layer. So insert the M600 command on the last layer(7.2mm). The better finished is archived if you print the last two layers in 0.1 layer height and enter the magnets on the second to last layer at 7.1mm. That increases the chances that the magnets get properly covered with filament.
![Slice2](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice2.JPG)


#### Position of the Pockets for the Magnets


![Slice3](https://github.com/Runningtarrens/Mcorne-c5/blob/main/pictures/slice3.JPG)



### Bottom

The Bottom part is a bit more complex. It has, if you choose magnetig tenting and a transparent basis, 3 pauses. 2 to get the magnets in and 1 to just change the filament. If you dont want magnetic tenting and dont want another colour for the top part, youll only need one pause for the magnets.

#### Overview of the Part.

![MagneticCorne7](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bottom%20slice.JPG)

#### First pause for the round magnets needed for the tenting

![MagneticCorne8](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bot%20slice%201.JPG)


#### Second pause to change the filament (different colour)

![MagneticCorne9](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bot%20slice%202.JPG)


#### Third pause for the magnets to close the case

![MagneticCorne10](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bot%20slice%203.JPG)


### Tenting Legs

![MagneticTentingLegs](https://github.com/Runningtarrens/Mcorne/blob/main/pics/tenting%20legs.JPG)

Print 4 of them upright. But you need a prim to have enough surface that sticks to the build plate or it will get loose while printing.





