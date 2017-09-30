# Pi-Compute-3-Lite-BLANK
Blank Kicad schematic for using the Pi CM3L.

The schematic will require some custom parts that are included in the .lib files. Custom libraries can be linked to in Kicad. The schematic contains everything required to get the CM3L to run. The rest of the pins are free to be used for any project. These files are meant to help jumpstart a project that wants to build around the CM3L.

Known Issues:
  1) If the fuse (MF-MSMF200) symbol does not show up in the schematic, hover over the component and hit 'e' to edit. Switching the "Chip Name" from "F_Small" to "Fuse_Small" should fix the issue. The names of the components in the built-in libraries has changed over different versions of KiCad.
