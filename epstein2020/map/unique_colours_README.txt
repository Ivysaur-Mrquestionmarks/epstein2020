Written by Mechano for use with Old World Blues.

Works with: GIMP, or manually reading the file with any text program.
Requires Java: https://java.com/en/download/

Description: This program is for creating maps in Hearts of Iron 4. It generates random colours, ensuring no repeats for use in creating province RGB values, then compiles them into a GIMP readable .gpl palette file.

Source Code can be found in the file "colour_generator.java".
=====================================

How to Use:
1: The main "unique_colours.jar" file can either be located in Documents/Paradox Interactive/Hearts of Iron 4/map, or mod/map. If it's located in Documents/Paradox Interactive/Hearts of Iron 4/Map, This will make it so that each time you add new provinces, all that must be done is that you load the game. By doing this, the definitions file updates automatically upon load. If it is located in the mod/map folder, you must take the definitions.csv from Documents/Paradox Interactive/Hearts of Iron 4/map and paste it into your mod/map folder, replacing the definitions.csv inside.

2: Simply double click the .jar file, it will generate a file with the extension ".gpl" called "unique_colours". If you just want the colours inside, the first 3 numbers on any line represent the Red Green Blue (RGB) values respectively.

NOTE: 3 & 4 are optional, but recommended for GIMP users. Manually using it by opening up the text file will also work.

3:  Setup the newly generated Palette file with GIMP. In GIMP, go to Windows(top right) -> Dockable Dialogs -> Palettes (between the middle and bottom). Right click anywhere inside the scroll bar -> Import Palette -> Palette File -> Find where this file is located (it's recommended you favourite this when you find this folder by clicking on the "+" sign on the bottom left) -> Open.

4: With your newly imported file, just select any colour within the dialog box and GIMP will automatically set that to your brush colour, you can manually check the palette colours RGB by double clicking. It's recommended you go sequentially within this from top left to bottom right, keeping track of already used colours within the palette. Each generated palette has 999 colours, if you forget where you are within a palette, want more colours etc. just restart this process and an accurate, brand new palette file will generated.
