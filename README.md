# Max-Payne-Fix-Windows-10
# NB! The creator of this fix is not responsible if something will go wrong during install,or for any issues that arise on your OS/hardware.This fix is distributed under GPL 3.0 license.This tutorial is meant for enthusiasts,tinkerers and gamers who want the the game to work and are not affraid to take the risk of learning some new stuff in the process

# To Fix the sound and limit FPS to 60:

0. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play and .NET 3.5 Framework support

1. Put all the files into the C:\Program Files (x86)\Steam\steamapps\common\Max Payne

2. Run the MaxBatch bat file

3. For sound fix just launch the C option and wait for the files to convert

4. Type E to exit the script.

5. When launching Max Payne on Windows 11 or Windows 10 in the Options select Enable Task Switching.

6. (Optional) To avoid seeing white texture shapes in game leave Antialiasing on off when configuring graphics options.

# NB! Only for AMD CPUs USERS JPEG issues fix:
6 Replace rlmfc.dll in C:\Program Files (x86)\Steam\steamapps\common\Max Payne with the one provided in the FOR AMD CPUs Fix folder in this repo

# NB! Dual Laptop GPU's ONLY!
1. Donwload everything extract
2. Copy all files from Reshade Dual GPU's Laptops folder C:\Program Files (x86)\Steam\steamapps\common\Max Payne 
3. Go to your NVIDIA Control Panel>3D Settings>Global find the preferred GPU and set it to NVIDIA
4. Run the MaxBatch bat file
5. For sound fix just launch the C option and wait for the files to convert
6. Type E to exit the script.
7. Enjoy

# (Optional) Bonus maximize difficulty settings via registry
0. Launch the game at least once and play the tutorial level for a bit.Exit
1. Start Menu->Run and type in regedit. Press Enter. 
2. Go to HKEY_CURRENT_USER->Software->Remedy Entertainment->Max Payne. 
3. Click on the 'Game Level' folder, and some items will appear on the right side of the screen. 
4. Right-Click and select New-DWORD Value 
5. Double-Click on the entry you just made and set the value to 1. 
6. Rename the entries to the following:
* hell for Dead On Arrival mode
* nightmare for Hard-Broiled mode
* timedmode for New York Minute mode

# NB! This fix needs to be used on a clean/fresh version of Max Payne installed it will not work with a bunch of other stuff installed because of API conflicts(software layer),same as any other fix
1. Uninstall Max Payne
2. Delete the Max Payne folder in C:\Program Files (x86)\Steam\steamapps\common\
3. Download all the files in the repo
4. Copy Paste into C:\Program Files (x86)\Steam\steamapps\common\Max Payne
4. Run the MaxBatch file again
5. Press C wait for files to convert then E
6. Launch game

# Added 60FPS support for 1080p Thirteen AG patch.
1. Download and extract. 
2. Copy and paste the Sound Patch folder first into your C:\Program Files (x86)\Steam\steamapps\common\Max Payne
3. Use the sound patch.Convert files.Exit
4. Launch Game at least once!
5. Copy and paste the rest of the MaxPayne 60 FPS Lock and 1080p Patch folder 6 files: d3d8.dll d3d9.dll d3d9.ini global.ini MaxPayne.WidescreenFix.asi MaxPayne.WidescreenFix.ini into Max Payne folder C:\Program Files (x86)\Steam\steamapps\common\Max Payne

# Max Payne Fix Linux With Thirteen AG Patch and 60 FPS lock

1. Install Mangohud for your distro

2. Download Max Payne Fix Linux from here or from Thirteen AG Repositiory and extract into the game folder:
    
https://thirteenag.github.io/wfp#mp1

4. Go to Steam>Max Payne>Compatibility>General>Launch Options

5. WINEDLLOVERRIDES="d3d8=n,b" MANGOHUD_CONFIG="fps_limit=60,no_display" mangohud %command% -skipstartup

6. If you are on AMD CPU replace rlmfc.dll in Max Payne directory with the one provided here in the FOR AMD CPUs Fix folder in this repo or download it here

https://drive.google.com/file/d/1nPUgYVdj03J1jI0CONMrPit0snFN9P4_/view

6. Enjoy the game

7. At the time of testing the Steam versin of Proton 9.0.1

# Enjoy the game,credit goes to Darkje for the Sound Patch creation and ThirteenAG for the wrapper creation visit his website for more goodies:https://thirteenag.github.io/wfp!
# Thanks goes to silentgamepls for setting it up,testing and configuring the wrappers to be recognized by the game and setting the FPS limit.
# Enjoy!
# silentgameplays
