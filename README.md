# Xbox-v1.6-128MB-Upgrade-Installation-Tools
## Summary
A set of tools to ease the difficult 128MB upgrade on the Xbox v1.6, by bending the RAM chip pins to match the angle of the lower chip, and an alignment tool to place the additional RAM chip.

There are two tools, each in their own folder.
- Each folder will contain instructions and calculations
- The 3D model source file, created using FreeCAD
- The STL file of the model, ready for 3D printing

**NOTE:** A video that shows how to use these tools is posted on YouTube here:
[YouTube_Video]

## Printing the tools
Use a quality 3D printer, using a smaller nozzle for the most accurate print. The prototype tools printed by EXP Systems were printed as follows:
- 3D printer: Prusa MK4S
- Filament: PLA
- Nozzle: 0.25 mm

If you have any concerns about the accuracy of your print, measure the external size of the base.
- The design is **41.97** x **35.98** mm
- The prototype parts (3 parts) measured as **41.76-42.02** x **35.81-36.10** mm
  *Note: all three parts worked fine.*

## Instructions - Pin Folding Tool
The pin folding tool is made of two parts:
1. The **Base**, on which the RAM chip is placed.
2. The **Cover**, used by aligning with the base, and then pressing down to bend the pins to the new shape optimized to align with the RAM chip that will piggy-back on top of the existing chip on the Xbox 1.6

Here are the step-by-step instructions:
*Note: refer to the instructions.png image.*

**Step 1**. Insert the RAM chip into the base, making sure that the clocking mark is aligned with the matching mark on the tool. The clocking mark on the ship is the smaller circle in the lower left when looing at the chip from the top, with the text right side up.

**Step 2**. Align the Cover with the Base such that the one-way notch between the Cover and Base are aligned. Gently slide the Cover down until it reaches the top of the chip. Optional: You can now pickup the Base and Cover as a unit, to inspect that the pins are aligned in the tool on each side.

**Step 3**. With the Base and Cover on the table, press down on the Cover onto the Base to bend the pins using mnoderate force, and as evenly as possible. Even if one side bends first, continue pressing until all sides are seated. The tool is designed now to damage the chip or the pins if excessive force is used, nonetheless, once the pins are bent, there is no reason to press any further, or to press harder.

**Step 4**. Remove the Cover by sliding it upwards and away from the Base.

**Step 5**. The chip will likely be slightly pressed into the Cover (or, less likely, the Base). Use a pen or the erasor end of a pencil through the hole of the Cover (or Base) to pop it out of the tool (make sure to be only an inch (2 cm) above your table surface. Inspect the chip to make sure that:
- All pins are bent the same/evenly, and
- Pin 28 (the Chip Select Pin) was not bent, as it must not be connected to the chip on the motherboard.

<img width="1593" height="702" alt="Instructions" src="https://github.com/user-attachments/assets/08e9663c-f1be-4b85-a1d0-b927df6e1439" />

## Instructions - Chip Alignment Tool
**Step 1**. Gently align the Chip Alignment Tool with an existing RAM chip on the motherboard. It is important that you do not force it down, but you may find a very light "click" as it comes down. It is best to lower the tool at an angle to have one outside leg go down first against the motherboard and aligned with the pin, then lower the center leg next, and the third outside leg last. Once down, gently confirm that the tool is snug and does not move.

**Step 2**. Place a finger on the half-circle of the alignment tool to prevent any motion, and then gently insert the new RAM chip at an angle (long side is lower) into the alignment tool and lower it slowly/vertically until it is fully down on top of the existing RAM chip on the motherboard. You can use tweezers or fingers to place the new RAM chip - whichever you feel most comfortable with. If the new RAM chip does not align well, do not force it: remove it and try again.

**Step 3**. Inspect both the long and short sides that are readily visible: if both sides show that the two RAM chip pins are aligned, then all pins are aligned.

**Step 4**. Using two fingers on one hand, apply light pressure to the alignment tool half-circle and to the top RAM chip, and solder two pins, on the short side, and one on the long side, opposite from each other. *Note: there are multiple soldering techniques of these RAM chips, so checkout demonstrations on youtube, and choose the one that makes sense to you.*

**Step 5**. Apply light one finger pressure to the top chip, and gently remove the alignment tool.

**Step 6**. Inspect all four sides to ensure that all pins are still aligneed.

**Step 7**. Proceed with soldering the remaining pins, and connecting the Chip Select (CS) pin to the appropriate location on the motherboard.

