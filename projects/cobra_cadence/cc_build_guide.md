# Cobra Cadence build guide
<span style="font-size:18pt; color:red;">|||--This page is still under construction--|||</span>

> [!CAUTION]
> I'm writing this build guide, as well as the rest of this write-up while I'm away and don't have access to the keyboard. I might make some small mistakes, but these should be minimal. More likely, since I can't take new pictures, I'm relying on old pictures and some renders I can make while on the go.  
> It's not ideal but the best I can do right now. Feel free to open an issue on the [repo of this webiste](https://github.com/mreel/TiboLoete), and I'll do my best to fix it.

See the needed components [here](cc_main_page.md#Components)!

## Step by step
### Overview
1. Get components  
2. Prep case with threaded inserts and embedded nut
3. Put switches in the plate  
4. Wire the matrix
5. Connect matrix to controller
6. Put plate assembly into case
7. Connect both halves
8. Close everything up
9. Put on keycaps

### Getting components
All the used components should be fairly easy to find online, with the exception of the case as it's 3D-printed. The print files can be found in the `hardware` folder.  
The top half and the plates can be printed without supports (the top should be upside down for printing), though the bottom needs support. Printing upside down would likely create cleaner results on the bottom (visible) part of the case, but I decided to print right side up as it's a world of difference in terms of printing time and material usage.  

### Prep case with threaded inserts and embedded nut
There's 12 screws per half, meaning 24 threaded inserts per half. They should be pushed in with a soldering iron, the plastic will reflow around the ribs of the inserts and they should be solid.
#### Top half
The threaded inserts in the top case are pressed in from the bottom, as they are not visible from the top. Make sure to get them (at least) flush with the bottom of the case, otherwise the case won't close properly.

#### Bottom half
Analogous to the top half, the threaded inserts are pressed in from the top, again make sure they are flush.  

The bottom half also features an embedded M2 nut, for locking the connecting wire between halves in place. In theory it you could just drop in it in the slot, in practice it might need either some percussive persuasion or glue.

### Put switches in the plate  
Simple enough!  

### Wire the matrix
Now comes the ~~fun~~ ~~annoying~~ <ins>exciting</ins> part!  
Wire the matrix according to the wiring diagram below (todo), remembering to put diodes in between the switch and the row wires, with the black part of the diode facing away form the switch.  

The wiring might look a little funky, that's because it is. I wanted to keep the amount of wires to a minimum, which means the _mash!_ keys are -electronically- on the same row as the top of the main cluster, except for the pinky column. It's weird, but can be, and is, fixed in the firmware.  

![Matrix Wiring](media/wiring_matrix.jpg)  
<sup>It won't look this nice in real life</sup>

### Connect matrix to controller
### Put plate assembly into case
### Connect both halves
### Close everything up
### Put on keycaps