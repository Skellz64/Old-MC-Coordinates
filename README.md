# Old-MC-Coordinates

This is a simple jarmod that adds coordinates to Minecraft Alpha and Infdev debug screens.

Works for Minecraft versions ranging from inf-20100227 to a1.1.2_01 (see downloads). These versions utilize infinte world generation, where coords are missing but needed. Notch didn't add coordinates until a1.2.3.

<code style="color : gray">support for versions following a1.2.3 may happen in the future</code>

# Features

The display is based off of Notch's original implementation of coordinates in Alpha... xyz and f on separate lines.

There are two display options: 

The "revised" display (left) and the unmodified "nostalgia" display (right). 
This was done in case some are looking for the OG display by Notch before the various improvements were made in later versions. 

<img src="https://github.com/Skellz64/Old-MC-Coordinates/blob/main/revised_display.png" width="400" height="211"> <img src="https://github.com/Skellz64/Old-MC-Coordinates/blob/main/nostalgia_display.png" width="400" height="211">

These can be toggled using the <code style="color : gray">N</code> key with the debug screen on. By default, the revised display is shown.

The revised display simply improves the OG format: 

- rounds 15 leading decimals to 3
- brightens text color
- adds cardinal directions in words
- floors the y-axis to feet level (64.000 and not 65.620 when standing on a full block at y-64).

# Downloads

Due to various unforseen circumstances in older versions, I haven't modded every version (yet) from inf-20100227 to a1.1.2_01. I managed to mod 39 versions in this range, addressing for the more notable releases. Hopefully you can find the version you're looking for. 

[Coordinates_v1.0 Version Folder](https://github.com/Skellz64/Old-MC-Coordinates/tree/main/Coordinates_v1.0)

<code style="color : gray">the downloads are named "Coordinates_v1.0_" followed by "(version name)" ensure that you are downloading the correct version</code>

# How to install

Install [Java 8](https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html) , most mods for older versions use Java 8. So it's always a good idea to have it.

This is a jarmod so I recommend using MultiMC, PrismLauncher, or Betacraft v2.0. These launchers allow for jarmods to be easily setup older versions. They all have similar ways of adding jarmods... Edit your instance in said launcher, locate the <code style="color : gray">add to Minecraft.jar</code> button, and open the downloaded coords.zip.

For Betacraft v1.0, it's more complex as you will need to jarmod the version yourself. You will also need a zip explorer (I like WinRAR for Windows)

- after downloading coords.zip for prefered version, open the hidden <code style="color : gray">%appdata%</code> folder
- open the <code style="color : gray">.betacraft</code> folder
- open the <code style="color : gray">versions</code> folder
- highlight and right click on the version.jar you are using (ex: <code style="color : gray">a1.1.2_01.jar</code>)
- after right click, you can choose <code style="color : gray">Open with WinRAR</code>
- with the jar open, also open the downloaded coords.zip
- move the single <code style="color : gray">.class</code> file from coords.zip to the opened version.jar.
- Press <code style="color : gray">OK</code> , done! You successfully replaced a game file with my modded game file!
- Relaunch Betacraft v1.0 and play.
