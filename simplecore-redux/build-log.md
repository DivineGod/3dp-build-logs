# SimpleCore Redux Build Log

These are my notes for building the [SimpleCore Redux][simplecore-redux] by [Rolohaun][rolohaun] and [Chaz][chaz]

# Frame

I ordered the Funssorlab Frame Kit and it arrived 2025-12-23 in the afternoon.

## Parts Needed

 - Funssor Frame kit, except un-tapped 300mm extrusion, bed frame extrusions (the two smallest extrusions

## Assembling the frame

Putting the frame together with the blind joints was really easy.

I recommend putting in the 22 screws into the ends of the 11 350mm extrusions that are drilled and tapped. Note that there's a spare extrusion with no tapped holes. This is the X-axis extrusion.

Slide one 350mm extrusion into the ends of two of the 500mm extrusions, making sure that the extrusions are lined up the same way and that the gantry holes are the furthest away as we're connecting the bottom of the frame first. Then tighten the screws enough that nothing slides out.

Repeat with the other set of 500mm extrusions and a 350mm extrusion between those. Again, making sure the 500mm extrusions are oriented the same way as the first pair.

Next, slide in a 350mm extrusion between the pair of uprights. Tighetening the screws enough to not slide out. Repeat with another 350mm extrusion to complete the bottom part of the frame.

Now onto the gantry extrusions. One at a time, carefully slide down an extrusion to the point where the screw lines up with the gantry holes. Tighten the screws enough to keep the extrusion in place. Repeat two more times for a total of 3 gantry extrusions.

Complete the frame by adding the top 350mm extrusions.

## Squaring and aligning the frame

The frame is now roughly put together and it's easier for us to handle. Place the frame on a stable, flat surface. Loosen two corners of screws and using an extrusion, a machinist triangle or a 1-2-3 block, make sure the 350mm extrusion is lined up with the upright 500mm extrusion and they both are flush to the bottom surface, then tighten the screw, carefully making sure the alignment is ensured. Repeat all the way around. I like to work on one extrusion at a time loosening both ends at the same time, squaring and tightening, before moving to the next.

Given the use of well machined extrusions and bliend joints most of the squaring work is already done for us.

## Squaring and aligning the gantry

Using the 138mm tool to line up one end of a gantry extrusion with the top of the frame, then tighten the screw. Do this for each of the three extrusions in turn one-by-one.


# Feet

The z axis components extend below the bottom of the frame so as part of assembling the z-axis rails we need to also put on the feet.

### Parts Needed

 - 4 Printed feet
 - 12 M5x10mm Button Head  Screws
 - 12 M5 T-nuts

### Assembly

For each of the for feet attach loosely the 3 T-nuts with the 3 M5x10mm Button Head Screws.

Place the t-nuts into the 2020 extrusion on each corner tightening the screws until the feet are securely fastened


# Gantry

## Y Rails

Next up we will add the gantry rails on. Make sure the rails are cleaned and lubed, ready to be put on.

### Parts Needed

 - 2 MGN9H 300mm Rails
 - 16 M3x8mm Button Head Screws
 - 16 M3 T-nuts
 - Alignment tool 2020xMGN9

### Assembly

The rails go on the left and right side gantry extrusions.

First we make sure to add the screws and t-nuts very loosely to each rail. This allows us to put the rails on to the extrusion and then tighten up each screw to secure the rail.

For each side we put the extrusion as far back on the extrusion as possible. Position a rail/extrusion elignment tool for 2020 extrusion and 9mm rails close to the end screw hole, but not covering it. Tighten the screw enough the make sure the rail doesn't move too much. Then repeat with the other end. Slide the elignment tool up and down while tightening the middle screws until the rail is secure. Go over each screw and tighten completely.

## XY Gantry

### Parts Needed

 - 350mm Extrusion un-tapped
 - 300mm MGN9H Linear Rail
 - Printed XY joints
 - Printed spacers
 - 4 D5x30mm Shafts
 - X M3x8mm Button Head Screws
 - X M3 T-nuts
 - 8 M5x10mm Button Head Screws
 - 8 M5 T-nuts
 - 2 20T 10mm tall idlers
 - 4 F695 Flanged Bearings
 - 8 1mm spacer
 - 4 0.5mm spacer
 - 8 M3x6mm Button Head Screws

### Assembly

First we need to add the idler stacks to each of the printed XY-joints. This is a bit fiddly and does require patience and some amount of force.

#### Right XY-Joint

For the F695 bearing stacks push in the the D5x30mm through the larger of the idler stack holes in the square corner of the XY-Joint. Then put the following components on the shaft, while pushing it further:

 1. 10mm printed spacer
 2. 0.5mm steel spacer
 3. F695 Bearing (flange towards spacers)
 4. 1mm steel spacer
 5. F695 Bearing (flange opposite)
 6. 0.5mm steel spacer
 7. 1mm steel spacer

The toothed idler stacks repeats the same process in the triangular corner:

 1. 1mm steel spacer
 2. 10mm tall 20T Idler
 3. 1mm steel spacer
 4. Printed spacero

Add four sets of M5x10mm Screw and M5 T-nut to the XY-joint block. Don't tighten too much as we will need to be able to slide on the X-axis extrusion later

#### Left XY-Joint

For the F695 bearing stacks push in the the D5x30mm through the larger of the idler stack holes in the square corner of the XY-Joint. Then put the following components on the shaft, while pushing it further:

 1. 1mm steel spacer
 2. 0.5mm steel spacer
 3. F695 Bearing (flange opposite)
 4. 1mm steel spacer
 5. F695 Bearing (flange towards spacers)
 6. 0.5mm steel spacer
 7. 10mm printed spacer

The toothed idler stacks repeats the same process in the triangular corner:

 1. Printed spacer
 2. 1mm steel spacer
 3. 10mm tall 20T Idler
 4. 1mm steel spacer

Add four sets of M5x10mm Screw and M5 T-nut to the XY-joint block. Don't tighten too much as we will need to be able to slide on the X-axis extrusion later

#### Installation

Using four M3x6mm per side affix each XY-joint to the MGN9H Rail Carriage block. Tightening the screws with an allen key through the holes at the top of the printed part.

Slide the 2020 X-Axis extrusion through one side of the joints to the other side making sure the ends line up on each side. Tighten the screws to lock in the extrusion.


## Rear Idlers

The CAD shows smoothed idlers using F695 bearing. This, however, can lead to extra VFAs due to the teeth of the belt running over the smooth idler bearings. To combat this I've decided to use 8.5mm tall 20T idlers that are 15mm

### Parts Needed

 - Left and Right Idler Printed parts
 - 2 D5x30mm Shafts
 - 4 20T 8.5mm tall idlers
 - 6 1mm steel spacers
 - 4 M5x10mm Button Head Screw
 - 4 M5 T-nuts

### Assembly

Like the gantry XY-joint idler stacks slowly press a D5x30mm shaft through the top hole, then in order add the following:

 1. 1mm steel spacer
 2. 20T 8.5mm tall idler
 3. 1mm steel spacer
 4. 20T 8.5mm tall idler
 5. 1mm steel spacer

Then add the two M5x10mm button head screws and two M5 T-nuts to one set of mounting holes (either works, the other set will be addressed later)

Add the idler blocks to the rear upright extrusions above the gantry. Slide the X gantry to the rear and line up the rear idler block such that the 10mm 20T idler lines up with the 20T 8.5mm idler opposite, either top or bottom. The plastic parts should also ideally line up in this case. Tighten the M5 screws.

## Front Motors

I've chosen to use the optional double shear motor mount to ensure motion system performance.

### Parts Needed

**TODO**

 - 2 Stepper Motors
 - 2 20T Pulleys
 - 2 F695 Flanged Bearings
 - 4 M5x10mm Button Head Screws
 - 4 M5 T-nuts
 - 8 M3x25mm Button Head Screws

### Assembly

**Fix this**

Pulley on motor shaft.
Bearing in double shear printed part.
M5 Screws and T-nuts in motor mount printed part.
Mount loosely on upright extrusion.
Place motor with pulley on mount.
Screw double shear print to the motor through motor mount holes with M3x25mm button head screws.


## Z-axis Rails

### Parts Needed

3 Gearboxes:

 - 3 Z-axis Motors
 - 3 Z-motor mount Printed Parts (2 are the same, one is mirrored)
 - 6 M3x12mm Button Head Screws for motor mounts locking
 - 6 M5x10mm Button Head Screws
 - 3 M3x8mm Button Head Screws for motor mounts pivot
 - 6 M5 T-nuts
 - 3 80T Gears
 - 6 20T Pulleys
 - 3 Closed Loop 188mm belts
 - 3 5mmx60mm Shafts
 - 6 F695 bearings

3 Top Mounts:

 - 6 M5x10mm Button Head Screws
 - 6 M5 T-nuts
 - 3 Top Extrusion Mount Printed Parts
 - 3 Belt Tensioner Printed Parts
 - 3 M3x5ODx4L Heatset Inserts
 - 3 M3x12mm Button Head Screws
 - 3 D5x20mm Shaft
 - 3 20T Idlers
 - 6 M3x12 Button Head Screws for Rail
 - 6 M3 Nylock heax nuts for Rail

Extra:

 - Z Front Rail alignment tool
 - Z Rear Rail alignment tool
 - 3 MGN12H 300mm rails

### Gearbox assembly

Repeat three times.

To the stepper motor shaft add a 20T Pulley teeth side out. Do not fully tighten it.

Add two M5x10mm button head screws and 2 t-nuts to the vertical holes that will eventually mount to the 2020 extrusion.

Mount the motor to the gearbox in the pivoting corner with an M3x8mm button head screw.

Insert two F695 bearings in the bearing holders. Slide in a 5mmx60mm D-Shaft while making sure to also add a 20T Pulley to the shaft between the two bearings.

Add the 80T Gear to the outside on the side where the motor tensioning mount is located. Make sure the end of the shaft is flush with the end of the gear closest to the teeth.

Put a 188mm Closed loop belt on the 20T pulley then gently slide the belt over the 80T Gear while rotating the gear to fully locate the belt correctly around both.

Fix the position of the 20T Pulley on the stepper motor shaft such that it lines up with the 80T Gear. Make sure that when fully rotated no part of the belt rubs on the sides of either gear.

Mount the gearbox loosely to a 2020 extrusion as it needs to slide around to find the perfect spot when the rail is attached.

### Top mounts

Loosely attach two M5x10mm button head screws through the mounting holes with two M5 T-nuts on the top extrusion mounts.

Place the blocks on the gantry 2020 extrusions. One roughly in the center at the rear and the other two towards the front on either side.

### Rails

Attach each rail to the corresponding gearbox and top mount with two M3x12mm screw and matching M3 Nylock nuts.
### Belt tensioning blocks

Prepare the idler tensioner block with heatset inserts by pressing them in from the inside, cleaning up any plastic that might have pooled on the outside by putting a screw partway through and using a sharp tool to clean the edges.

Insert the 20T Idler in the mount and press the D5x20mm shaft through until flush.

Mount the Idler block in the top mount printed part with an M3x12mm button head screw.


### Belts

** TBD **

## Bed

** TBD **


## Toolhead

## Electronics



[simplecore-redux]: ahttps://www.printables.com/model/1476384-front-mounted-rail-for-simplecore-redux
[rolohaun]: https://www.youtube.com/@Rolohaun
[chaz]: https://www.youtube.com/@ChazMakes
