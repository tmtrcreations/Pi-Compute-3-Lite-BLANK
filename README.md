# Pi-Compute-3-Lite-BLANK
Blank KiCad schematic for using the Pi CM3L.

******************************************
* PROJECT WAS CREATED WITH KICAD V4.0.4! *
******************************************

The schematic will require some custom parts that are included in the .lib files. Custom libraries can be linked to in Eeschema (or placed in the same folder as the project). The schematic contains everything required to get the CM3L to run. The rest of the pins are free to be used for any project. These files are meant to help jumpstart a project that wants to build around the CM3L.

I have also recently added the footprints for the components as well. When you open Pcbnew to read the netlist, add the path to the Pi-Library.pretty folder first. Then when you read in the netlist, all of the components should show up with no errors.

Known Issues:
  1) Opening the schematic in newer versions of KiCad will cause issues with some of the component symbols (both orientation of the symbol and finding the correct symbol).
  2) If the fuse (MF-MSMF200) symbol does not show up in the schematic (when using a newer version of KiCad), hover over the component and hit 'e' to edit. Switching the "Chip Name" from "F_Small" to "Fuse_Small" should fix the issue. The names of the components in the built-in libraries have changed over different versions of KiCad.
