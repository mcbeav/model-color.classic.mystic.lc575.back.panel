
# Macintosh Color Classic Mystic LC575 Custom Back Panel Model

  

This repository contains models with different options for a custom back panel for the Macintosh Color Classic with the LC575 (Mystic) upgrade.

  

***I'll be pushing new configurations and options for the back panel, but I am uploading what I have available at the moment.***

  

### Preface

I was not happy with the tolerances and options with existing models for a back panel for a Macintosh Color Classic Mystic, so I designed a new one. I added icons to describe each port, a spot for an SD card slot for my internal BlueSCSI with an SD card extension, FloppyEMU support with a custom bracket, so I could plug in the FloppyEMU using a DB19 cable, and changed the expansion slots to specifically fit my Apple IIe card, and an Apple Ethernet card.

  

*I am NOT an engineer, nor do I have much experience with 3D modelling. These models fit my Color Classic Mystic perfect, but I can not guarantee they will fit yours perfectly.*

  

*My original model has very specific customizations that will likely not be helpful for you, so I am making some revisions and uploading a few more options. The model is also open source, so you can modify it to fit your needs.*

  

![Back Panel With All My Customizations](https://raw.githubusercontent.com/mcbeav/model-color.classic.mystic.lc575.back.panel/refs/heads/main/photos/installed.jpg)

  

![Back Panel With Everything Plugged In](https://raw.githubusercontent.com/mcbeav/model-color.classic.mystic.lc575.back.panel/refs/heads/main/photos/plugged.jpeg)

  

![Printed In Multiple Pieces & Plastic Welded Together](https://raw.githubusercontent.com/mcbeav/model-color.classic.mystic.lc575.back.panel/refs/heads/main/photos/printed.jpeg)

  
  

## Notes

  

Each model is split into 2 folders.

  

The ***single*** folder contains the model that can be printed as a single piece.

  

The ***layers*** folder contains the model split into pieces. This was done in an attempt to preserve details when being printed.

*I printed the bottom layer using a 0.2mm nozzle to preserve the details in the icons on the back panel. The inner layer and the inserts I printed using a standard 0.4mm nozzle. Everything fits together, and I plastic welded the pieces together, however glue would work just fine.*

  

The structure of this repository is probably confusing, so I'll do my best to outline how this is structured.

Folders:

**no-customizations**

 - this folder contains a stock / standard model of a back panel for a Color Classic Mystic with all the customizations removed.
	 - **single**
		 - contains the model that can be printed as a single piece
	 - **layers**
		 - contains the models split into layers that is printed in pieces and put together.
		 - this was done to preserve details

**customizations**

 - this folders contains different models with various customizations made to the back panel.
	 - **all-customizations**
		 - the model has customizations made that are very specific to my personal color classic mystic
		 - i've included it in case it is helpful for anyone else, but I don't think it will likely be the model you want to use. I wired up a janky circuit board to convert a FlippyFloppy from KayKoba to connect using a DB19 connector instead of the IDC20 ribbon connector. 

		 - ***customizations***:
			 - Custom FloppyEMU support modifying a FlippyFloppy, with a custom bracket for the DB19 conversion board
				 - added a port for the FlippyFloppy switch
			 - SD Card slot over the audio ports for the internal BlueSCSI that requires an SD card extension to be run internally
			 - There is hole to adjust a Spicy O' Clock, but that requires a custom bracket for the Spicy O' Clock, that I can not share without KayKoba's permission.
			 - The PDS slot size is adjusted to fit an Apple IIe card perfectly with no open space around the edges
			 - The PCI slot was changed to fit an Apple Ethernet card.
 
	 - **flippyfloppy-revision**
		 - the model was revised to support the standard IDC20 bracket that ships with the FlippyFloppy.

		 - ***customizations***:
			 - FlippyFloppy support
				 - added a port for the FlippyFloppy switch
			 -  SD Card slot over the audio ports for the internal BlueSCSI that requires an SD card extension to be run internally
			 - The PDS slot size is adjusted to fit an Apple IIe card perfectly with no open space around the edges
			 - The PCI slot was changed to fit an Apple Ethernet card.

	 - **standard-expansion-ports**

		- the model was revised to have more of a standard style expansion port slots with printable covers

		- ***customizations***:
			- FlippyFloppy support
				- added a port for the FlippyFloppy switch
			- SD Card slot over the audio ports for the internal BlueSCSI that requires an SD card extension to be run internally


***I'm working on a few more revisions. I'll update the repository as I complete and add new revisions.***

## Other Models Available For A Color Classic Mystic Back Panel

|**FloppyEMU Support (FlippyFloppy) - radar_939** |[https://www.printables.com/model/714780-mac-mystic-back-panel-for-flippy-floppy-support?lang=de](https://www.printables.com/model/714780-mac-mystic-back-panel-for-flippy-floppy-support?lang=de) |

|**Stock - PowerCC** |[https://powercc.org/downloads/](https://powercc.org/downloads) |

|**Stock - jon_pi** |[https://www.thingiverse.com/thing:5575698](https://www.thingiverse.com/thing:5575698) |