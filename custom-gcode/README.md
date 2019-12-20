# Whats Custom GCode?

In your slicer you can change the gcode that gets executed at different times, like when a print starts, on layer change, when a print ends, etc.

# How to change in Cura 4.1.0

Settings > Printer > Manage Printers

Find you machine, click Machine Settings

Paste your custom start or end code in the text areas.

Done.

# EZABL Note

EZABL is a thing you can buy that lets you accurately measure the distance to the bed from the nozzle. It makes life so much easier. If you don't have one, get one. It's worth.

https://www.th3dstudio.com/product/ezabl-pro-plug-print-auto-bed-leveling-kit/

ender3-ezabl-\*.txt has code that expects you to have an ezabl or something like it installed to do mesh generation. The only thing that's special to having an EZABL vs STOCK is the line:

    G29; EZABL mesh generation

If you don't have an EZABL, you can take that line out.
