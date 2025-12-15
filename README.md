# Switch-Icon-Changer
simple gui automates changing icons for nsps


![Capture](https://github.com/user-attachments/assets/b882737a-e376-429c-a4a3-62ea800e864b)



====================================
 Switch Icon Changer
 by The Other Side
====================================

This tool allows you to change the icon of Nintendo Switch NSP games
by rebuilding the Control NCA.

------------------------------------
 REQUIREMENTS
------------------------------------

You MUST provide your own keys file.

The following files must exist next to the EXE:

NSP-IconChanger.exe
decrypt.bat
ztools/
hactool.exe
hacpack.exe
keys.dat   ← YOU MUST ADD THIS

If keys.dat is missing, the program will not run.

------------------------------------
 HOW TO USE
------------------------------------

1. Place NSP-IconChanger.exe in a folder
2. Place decrypt.bat in the SAME folder
3. Create a folder named "ztools"
4. Put hactool.exe, hacpack.exe, and your keys.dat inside "ztools"
5. Run NSP-IconChanger.exe

------------------------------------
 ICON BEHAVIOR
------------------------------------

• If you SELECT an icon:
  - The game icon will be replaced

• If you DO NOT select an icon:
  - The existing icon inside the NSP is preserved
  - This does NOT restore the original icon unless the NSP is clean

------------------------------------
 IMPORTANT NOTES
------------------------------------

• This tool works with NSP files only
• Repacking a previously modified NSP will keep the modified icon
• Home Menu icon cache behavior is controlled by the Switch system
• Saves, updates, and DLC are NOT modified

------------------------------------
SUPPORTED NSP STRUCTURE
------------------------------------

This tool ONLY works with NSP files that contain:

• Control NCA
• Meta (CNMT) NCA

These are typically:
• Base game NSPs
• Properly dumped eShop titles

NSP files that DO NOT contain a Control NCA
or CNMT metadata will NOT work.

Examples of unsupported NSPs:
• Partial / stripped dumps
• Some ports with icon stored in RomFS
• Homebrew-forwarder style NSPs
• Custom or malformed NSPs

If your NSP does not include both:
• control.nca
• *.cnmt.nca / *.cnmt.xml

This tool cannot modify the icon.
------------------------------------
 LEGAL
------------------------------------

This tool does NOT include Nintendo keys.
You must dump your own keys from your own console.

This software is provided as-is.
Use at your own risk.
