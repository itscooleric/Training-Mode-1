# Training Mode - A Melee Modpack for Practicing Tech

Training Mode is a modpack for Super Smash Bros. Melee that aims to streamline practice by providing pre-made individual training scenarios. 
This mod utilizes the event mode present in Super Smash Bros. Melee and reworks them to focus around specific techniques, 
complete with automatic savestate functionality to allow for rapid-fire practice. Some events have included video tutorials playable 
in-game (ISO version only) to teach the player about the tech and how to perform it. In addition to these events, 
Training Mode also includes onscreen text displays which provide you with information otherwise unavailable to you mid-game. 

# How To Compile the ISO on Windows

1.) Fizzi36 wrote a program to mass assemble .asm files, it is included in the "Build TM Codeset" folder in this repository.
All you need to do is launch the "Build Training Mode Codeset.bat" file and the codes.gct file will be generated and placed in
the "Additional ISO Files" folder. This folder contains all the files you need to place into the ISO to run Training Mode minus
one file, the Start.dol. 

2.) The Start.dol is the game's executable and contains copyrighted code, so for that reason I cannot distribute it. 
However, if you manage to extract the Start.dol file out of your own ISO file you can patch the dol file to load
the codeset created prior. Look for the file named "Drag Melee v1.02 Start.dol Here.bat" located in the "Build TM Codeset" folder 
and drag your extracted 1.02 NTSC Start.dol file onto the .bat file. The modified Start.dol will also
be place in the "Additional ISO Files" folder.

3.) You can now copy the contents of "Additional ISO Files" to an NTSC 1.02 Melee root folder and rebuild the ISO. I recommend using
GCR.