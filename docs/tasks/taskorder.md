# Task Order

Columns:

* Task: links to the task instructions.
* Parts reqd: Shows purchased parts from the parts list that are required for the task. It generally does not list parts that were used in a previous task. It also does not list tools etc.
* Preceding Tasks: Shows tasks that need to be done before this one.
* Involves: This may be useful for grouping tasks. For example, refer to it to concurrently do all of the tasks that require soldering.
* Est time: In minutes. The times might be way off. Some times, indicated by **, do not take into account time required for glue to dry, during the task.

## Round One
These tasks have no preceding tasks and can be done concurrently.

| Task | Parts reqd | Involves | Est time |
| -- | -- | -- | --: |
| [BEC Prep](bec_prep.md) | [BECs](../parts/bec.md) | - | 10 |
| [XT to wires](xtwires.md) | [XT connectors](../parts/xt.md), [heat shrink](../parts/tapeetc.md), [wire](../parts/wire.md) | wire prep, solder, heat shrink | 90 |
| [XT to parts](xtparts.md) | [XT connectors](../parts/xt.md), [heat shrink](../parts/tapeetc.md), [BECs](../parts/bec.md), [Quad ESCs](../parts/quadesc.md) | wire prep, solder, heat shrink | 30 |
| [camera mount plates](cameraplates.md) | [Camera wood](../parts/camerawood.md) | cutting, drilling (or 3D print) | 120 |
| [radio mount](radio_mount.md) | [airframe](../parts/airframe.md), [radio](../parts/radio.md) | - | 10 |
| [plane motor mount](planemotor_mount.md) | [airframe](../parts/airframe.md) (one wood piece), [plane motor & prop & holder & bushing & stop](../parts/planemotor.md), [M3 8mm screws & nuts](../parts/hardware.md) | cutting, drilling | 45 |
| [quad ESC solder](quadesc_solder.md) | [quad ESCs](../parts/quadesc.md), [quad motors](../parts/quadmotor.md) | soldering | 60 |
| [bracket prep](bracket_prep.md) | [small brackets](../parts/brackets.md) | drilling and/or cutting (or 3D print) | 60 |
| [airspeed prep](airspeed_prep.md) | [airframe](../parts/airframe.md), [airspeed sensor](../parts/airspeed.md) | - | 15 |
| [servo setup](servo_setup.md) | [servos](../part/servos.md), [battery](..parts/battery.md), [XT90 to XT60 adapter](..parts/xt.md), [BEC](../parts/bec.md) | - | 15 |
| [GPS mount](gps_mount.md) | [GPS](../parts/flightcotroller.md) (included with flight controller), [airframe](../parts/airframe.md), [tapes](..parts/tapeetc.md) | - | 30 |
| [wood frame](wood_frame.md) | [airframe](../parts/airframe.md) | - | 30 |
| [receiver bind to transmitter](receiver_bind.md) | [receiver](../parts/receiver.md), [flight controller](flightcontroller.md) | - | 15 |
|  |  |  |  |

*The estimated times might be way off.

## Round Two
These tasks requires at least one "Round One" task to be done first.

| Task | Parts reqd | Preceding Tasks | Involves | Est time |
| -- | -- | -- | -- | --: |
| [quadarm prep](quadarm_prep.md) | [quadarm material](../parts/quadarm.md), [hardware](../parts/screwsetc.md) | [bracket prep](bracket_prep.md) | cutting, drilling (incl of pultruded carbon fiber), maybe 3D printing | 120 |
| [camera assemble](camera_assemble.md) | [camera, lens](../parts/camera.md), [dampers](../parts/cameradampers.md), [2-56 screws & nuts](../parts/screwsetc.md) | [camera mount plates](cameraplates.md) | - | 15 |
| [plane ESC mount](planeesc_mount.md) | [airframe](../parts/airframe.md), [plane ESC](../parts/planeesc.md), [glue & velcro tape](../parts/tapeetc.md) | [plane motor mount](planemotor_mount.md) | - | 10 |
| [fuselage prep](fuselage_prep.md) | [airframe](../parts/airframe.md), [spacers](../parts/screwsetc.md), [GPS](../parts/flightcontroller.md) | [quadarm prep](quadarm_prep.md), [camera plates](cameraplates.md) | - | 60 |
| [receiver mount](receiver_mount.md) | [airframe](../parts/airframe.md), [receiver](../parts/recevier.md), [tape & velcro tape](../parts/tapeetc.md) | [receiver bind](receiver_bind.md) | - | 30 |
| [power loom nodes](nodes.md) | [wire](../parts/wire.md), [heat shrink](../parts/tapeetc.md), [PM02 incl with flight controller](../parts/flightcontroller.md) | [XT to wires](xtwires.md) | wire prep, solder, heat shrink | 120 |
| [radio wires](radio_wires.md) | [radio](radio.md) | [BEC prep](bec_prep.md) | - | 10 |
| [tail setup](tail_setup.md) | [airframe](../parts/airframe.md), [radio antenna](../parts/radio_antenna.md), [glue & tape](../parts/tapeetc.md), [servo lead extensions](../parts/servoext.md) | [servo setup](servo_setup.md) | gluing | 60\*\* |
| [wing setup](wing_setup.md) | [airframe](../parts/airframe.md), [glue & tape](../parts/tapeetc.md), [servo lead extensions](../parts/servoext.md) | [servo setup](servo_setup.md), [GPS mount](gps_mount.md) | gluing | 45\*\* |
| [frame brackets](frame_brackets.md) | [flight controller](../parts/flightcontroller.md), [screws](../parts/screwsetc.md) | [bracket prep](bracket_prep.md), [wood frame](wood_frame.md) | - | 20 |
|  |  |  |  |  |

\*The estimated times might be way off.  
\*\*Does not take into account time required for glue to dry, during the task.

## Round Three
These tasks requires at least one "Round Two" task to be done first.

| Task | Parts reqd | Preceding Tasks | Involves | Est time |
| -- | -- | -- | -- | --: |
| [quadarm assemble](quadarm_assemble.md) | [heat shrink](../parts/tapeetc.md). [screws](../parts/screwsetc.md) | [quadarm prep](quadarm_prep.md), [quad ESC solder](quadesc_solder.md) | heat shrink | 30 |
| [battery velcro](battery_velcro.md) | battery, airframe, velcro straps, velcro tape | [receiver mount](receiver_mount.md) | - | 20 |
| [tail glue](tail_glue.md) | [airframe](../parts/airframe.md), [glue](../parts/tapeetc.md) | [tail setup](tail_setup.md) | gluing | 30 |
|  |  |  |  |  |

## Round Four+
Remaining tasks and rounds.

| Round | Task | Parts reqd | Preceding Tasks | Involves | Est time |
| -- | -- | -- | -- | -- | --: |
| 4 | [Airframe Close](airframe_close.md) |  |  |  |  |
| 5 | [finish build](finish_build.md) |  |  |  |  |
|  |  |  |  |  |  |
