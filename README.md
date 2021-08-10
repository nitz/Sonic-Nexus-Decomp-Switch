# Sonic Nexus (2008, RSDK) Decompilation for the Nintendo Switch
A Full Decompilation of Sonic Nexus (2008) made by RDC, ported to Nintendo Switch via hackery using HeyJoeWay's CD switch port as a baseline.

# Installation Instructions

You can find downloads in releases.

   1. Make sure your Switch can run homebrew.
   2. Extract the contents of the zip to the root of your SD card.
   3. Copy the assets to /switch/nexus2008 on your Switch's SD card. You will need the following files/folders:
      
      Data.bin / Data Folder 
        
   (if you extracted the Data.bin. This lets you get Dev Menu support and solve a music loop issue present in Nexus (and also CD for some reason))

   4. Start Sonic Nexus via hbmenu.

NOTE: It is recommended to give the game full RAM access. This means you shouldn't launch hbmenu from the album applet when running this. With the latest Atmosphere build and its default config, you can hold R while starting any game to open hbmenu with full RAM access. If you have any issues make sure the game has full RAM access before reporting them; launching as an applet will not be supported.

# Known Bugs

There is an issue where not entering the title screen / intro via dev menu will lock up the game with a frame of the title screen with an odd color palette when starting the game. fix is to use Data.bin or actually load the Intro / Title with the dev menu using Start / A

There is also no way to press a button to access the dev menu. (hopefully can be figured out eventually)

# Contact:
Join the [Retro Engine Modding Discord Server](https://dc.railgun.works/retroengine) for any extra questions you may need to know about the decompilation or modding it.
