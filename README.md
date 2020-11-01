Developer blog post submitted January 04, 2012

There are two new versions of the Wiimote out now that have the Wii Motion Plus built into the Wii Remote itself. Both versions look like a regular Wii Remote, but with writing in a semicircle around the Wii logo at the bottom of the Wii Remote.

The first version is the original “Wii Remote Plus”, which behaves almost exactly like a normal Wiimote with a Wii Motion Plus extension plugged in the bottom. It is compatible with all the PC and Wii software that supported the original Wiimote. The gold Skyward Sword Wii Remote Plus is one of these, and so (for now) is the one that comes with WiiPlay Motion. Ones bought before November also tend to be this version, including some that came with Wii consoles. They come in all different colours. When you connect it to a computer it says “RVL-CNT-01″. If you open the battery compartment and look inside, it has a code like this: “LMB RVL WR/H-C0″, “LMA-RVL-WR/M-C0″, “LMB-RVL-WR/M-C0″, “LMA-RVL-WR/M-C2″, or “LMB-RVL-WR/Z-C2″. I think the important part is the last digit has to be less than 4.

The second version is the newer “Wii Remote Plus TR”, which doesn’t work with most PC software or with Wii Homebrew Channel, but works fine on all Wii Games, no matter how old. The packaging and outside is identical to the older version. This newer version came out in November. It seems to come in every colour EXCEPT GOLD. When connected to your computer, it says “RVL-CNT-01-TR”, and the PID will be 330H instead of 306H. If you open the battery compartment it has the code “LMB-RVL-WR/Z-C4″, or “LMB-RVL-WR/Z-C6″. A FEW (but not most) of these have a SYNC button on the OUTSIDE of the battery case.

If you have a Wii Remote Plus TR then GlovePIE 0.45 won’t work for you. But I made some modifications to use the new Product ID and the new Bluetooth name. I don’t know if that will be enough to make it work or not. Please test this new EXE file (you’ll need to put it with the contents of the GlovePIE 0.45 zip file too):

TestWiimotePlusTR.zip

and let me know how it works.
