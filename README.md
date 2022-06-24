# 86Box
System Configs and Setups for 86Box

I will be adding some system setups and documents for anyone using the 86Box virtual pc emulator.

Build V2.07 (Fixed in Build 3.x)
Mouse cursor corruption using ATI Graphics Pro Turbo (Mach64) in Windows 3.1 and 95.
This happens with all driver versions and resolutions including default Windows 95 driver.

Temporary Fix and Workaround
For Windows 95:
Change the mouse pointers scheme to 3D Pointers from within the mouse control panel.

Build V3.x (Working in Build 2.x)
PS/2 Mouse not working and slow responsive Bus Mouse.
Setting input device to PS/2 mouse does not give a usable mouse when installing Windows 3.x / 95 /98 systems.
I'm not sure if this is a bug or a driver issue but I cannot get a PS/2 mouse to work when using even the
CuteMouse driver CTMOUSE.EXE under DOS either.

I've found a fix for the slow jerky mouse issues with Build 3.x when using the Logitech/MS Bus mouse.
The problem is with the default Hz setting. Changing the value to non-timed (original) gives very smooth
mouse control and very good response.
