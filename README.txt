HISTBUFF.G4B v0.1 (20230411)
Grub4dos script to View, Check, Delete, Export, Import and Write to History Buffer (support for grud4efi is experimental)

Use: HISTBUFF.G4B

Main menu:
V to view number of History entries and view the full History Buffer
G to view the Command-line Buffer and the location on the used Grub4Dos-version
N to view the location of num_hist on the used Grub4Dos-version
T to test the function of the History Buffer and view the change
W to write a variable to the History Buffer and view the change
S to check for invalid entries in the History Buffer and synchronize num_hist
D to empty the History Buffer and set num_hist to zero
E to export the History Buffer to file (extension .KBC only)
I to import a History Buffer from file (earlier saved - .KBC only)
F to reverse order of all entries in the History Buffer and view changes
C to convert all valid entries in the History Buffer to text and export to file
K to get more information about the History Buffer
Q to quit HISTBUFF.G4B or restore History Buffer if wanted (after changes)
All Sub-menu's should be self-explaining or will provide instructions for use

Remarks: exported variables are NHistory HISTADDR HISTBUFF CMDLADDR SECT
         Tested on most recent version of grub4dos
         Tested on most recent version of grub4efi (BOOTX64.EFI only)

Version History:
V0.1
First version experimental support for grub4efi too (successor of KEYBUFF.G4B - grub4dos only)

More information about the whole project (starting at): http://reboot.pro/index.php?showtopic=22450&p=217925
