## Camera mount plates
This task makes 3 plates which will be used to mount the camera.

* The bottom plate goes on the exterior of the fuselage.
* The middle plate goes inside the fuselage, on the floor, and bolts to the bottom plate.
* The top plate sits above the middle plate, and they are attached to each other by damping balls.  

The plates can be 3d printed from the files in this project, or they can be fabricated out of thin plywood (.11" or 3mm) or another thin material.

After assembly the bottom plate will not be aligned with the other two plates -- It is 20mm longer, and the front edge of the bottom plate is shifted 25mm (1") forward of the other two. You could also say the holes in the bottom plate are shifted 15mm to the rear. The image below is for reference; in this task you are only making the plates. The extra material on the bottom plate helps it mate with the shape of the [mini talon](../parts/airframe.md).  
![camera mount without fuselage](../images/camera_mount.jpg)  

**Dimensions:** x and y are measured from the camera hole centers. x is side-to-side and y is forward/back.

| plate | length | width | hole shift | camera hole dia | notch dia | bolt1 dia | bolt1 x&y | bolt2 dia | bolt2 x | bolt2 y | damper dia | damper x | damper y |
| -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| **top** | 66 | 58 | 0 | **32** | **12** | 2.5 | 15 | **6** | 24 | 12 | 10 | 19 | 23 |
| **middle** | 66 | 58 | 0 | 38 | 9.5 |  |  | 3.5 | 24 | 12 | 10 | 19 | 23 |
| **bottom** | **86** | 58 | **15** | 38 | 9.5 |  |  | 3.5 | 24 | 12 |  |  |  |

All three plates have a notch on the left side of the lens hole. The notches give clearance for assembly and for the knobs on the camera lens. The notches can also be a starting point for cutting the lens holes.  

## steps ##
**here's one way**

1. start with three pieces that are longer and/or wider than needed. The extra material can be helpful to hold the pieces when cutting and drilling.  
1. **all 3** plates: mark the cut lines for length/width, per the table above.
1. **all 3** plates: Label the front and top of each plate. For example, write "fwd top bot" on the top of the forward-end of the bottom_plate.
1. **top and middle** plates: mark the camera hole center (in the middle of the plate)
1. **bottom** plate: mark the camera hole center (15mm back from the middle of the plate)
1. Mark the lens hole circumferences -- 32 mm dia for the **top** plate, 38 mm dia for the **other two** plates.
1. **Top** plate: mark the centers of the 4 "bolt1" holes that will align with the bolt holes on the raspberry pi camera. You can use the camera as a template, or just measure from the plate center: +/- 15mm in the x direction (side-to-side) and +/- 15mm in the y direction. You can label them "b1" for reference.
1. **All 3** plates: mark the centers of the 4 "bolt2" holes. Measured from the camera center they are +/- 24 mm to each side and +/- 12 mm forward/back. You can label them "b2" for reference.
1. **Top and mid** plates: mark the centers of the 4 "damper" holes. Measured from the camera center they are +/- 19 mm to each side and +/- 23 mm forward/back. You can label them "d" for reference.
1. Optional: line the plates up next to each other and see if the hole markings seem to line-up. See image above for reference.
1. **top plate**: drill the notch, 12mm diameter. It will be located 16mm left of center, aligning with the left edge of the camera hole.
1. **mid and bot** plate: drill the notch, 9.5mm diameter. Each will be located 19mm left of center, aligning with the left edge of each camera hole.
1. **top** plate: cut the lens hole, 32mm dia. You can use the notch as a starting place for a small saw blade, like on a hobby table saw.
1. **mid & bot** plates: cut the lens hole, 38mm dia.
1. **top** plate: drill the "bolt1" holes (4x). 2.5mm (3/32") dia.
1. **top & mid** plates: drill "damper" holes (4x each). 10mm (3/8") dia.
1. **top plate**: drill the "bolt2" holes (4x). 6mm (15/64") dia. The 6mm diameter allows the entire bolt, including the head, to be inserted all the way through the top plate where it will rest on the lower mid plate.
1. **top & mid** plates: drill the "bolt2" holes (4x each). 3.5mm (9/64") dia.
1. cut **all 3** plates to their final lengths and widths.
1. Optional: Check that the bottom plate fits well with the bottom of the fuselage.
1. Optional: Make sure all of the holes line-up for future assembly. See image above.
1. Deburr any sharp edges.
