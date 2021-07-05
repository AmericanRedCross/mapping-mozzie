# Task Order

Column notes:

* Parts reqd: Shows purchased parts from the parts list that are required for the task. It generally does not list parts that were used in a previous task. It also does not list tools etc.
* Involves: This may be useful for grouping tasks. For example, refer to it to concurrently do all of the tasks that require soldering.
* Est time: In minutes. The times might be way off. Some times, indicated by **, do not take into account time required for glue to dry, during the task.

## Round One
These tasks have no preceding tasks and can be done concurrently.

| Task | Parts reqd | Involves | Est time |
| -- | -- | -- | --: |
| [BEC Prep](tasks/bec_prep.md) | [BECs](parts/bec.md) | - | 10 |
| [XT to wires](tasks/xtwires.md) | [XT connectors](parts/xt.md), [heat shrink](parts/tapeetc.md), [wire](parts/wire.md) | wire prep, solder, heat shrink | 90 |
| [XT to parts](tasks/xtparts.md) | [XT connectors](parts/xt.md), [heat shrink](parts/tapeetc.md), [BECs](parts/bec.md), [Quad ESCs](parts/quadesc.md) | wire prep, solder, heat shrink | 30 |
| [camera mount plates](tasks/cameraplates.md) | [Camera wood](parts/camerawood.md) | cutting, drilling (or 3D print) | 120 |
| [radio mount](tasks/radio_mount.md) | [airframe](parts/airframe.md), [radio](parts/radio.md) | - | 10 |
| [plane motor mount](tasks/planemotor_mount.md) | [airframe](parts/airframe.md) (one wood piece), [plane motor & prop & holder & bushing & stop](parts/planemotor.md), [M3 8mm screws & nuts](parts/screwsetc.md) | cutting, drilling | 45 |
| [quad ESC solder](tasks/quadesc_solder.md) | [quad ESCs](parts/quadesc.md), [quad motors](parts/quadmotor.md) | soldering | 60 |
| [bracket prep](tasks/bracket_prep.md) | [small brackets](parts/brackets.md) | drilling and/or cutting (or 3D print) | 60 |
| [airspeed prep](tasks/airspeed_prep.md) | [airframe](parts/airframe.md), [airspeed sensor](parts/airspeed.md) | - | 15 |
| [servo setup](tasks/servo_setup.md) | [servos](parts/servos.md), [battery](parts/battery.md), [XT90 to XT60 adapter](parts/xt.md), [BEC](parts/bec.md) | - | 15 |
| [GPS mount](tasks/gps_mount.md) | [GPS](parts/flightcontroller.md) (included with flight controller), [airframe](parts/airframe.md), [tapes](parts/tapeetc.md) | - | 30 |
| [wood frame](tasks/wood_frame.md) | [airframe](parts/airframe.md) | - | 30 |
| [receiver bind to transmitter](tasks/receiver_bind.md) | [receiver](parts/receiver.md), [flight controller](parts/flightcontroller.md) | - | 15 |
|  |  |  |  |

*The estimated times might be way off.

## Round Two
These tasks requires at least one "Round One" task to be done first.

| Task | Parts reqd | Preceding Tasks | Involves | Est time |
| -- | -- | -- | -- | --: |
| [quadarm prep](tasks/quadarm_prep.md) | [quadarm material](parts/quadarm.md), [hardware](parts/screwsetc.md) | [bracket prep](tasks/bracket_prep.md) | cutting, drilling (incl of pultruded carbon fiber), maybe 3D printing | 120 |
| [camera assemble](tasks/camera_assemble.md) | [camera, lens](parts/camera.md), [dampers](parts/cameradampers.md), [2-56 screws & nuts](parts/screwsetc.md) | [camera mount plates](tasks/cameraplates.md) | - | 15 |
| [plane ESC mount](tasks/planeesc_mount.md) | [airframe](parts/airframe.md), [plane ESC](parts/planeesc.md), [glue & velcro tape](parts/tapeetc.md) | [plane motor mount](tasks/planemotor_mount.md) | - | 10 |
| [fuselage prep](tasks/fuselage_prep.md) | [airframe](parts/airframe.md), [spacers](parts/screwsetc.md), [GPS](parts/flightcontroller.md) | [quadarm prep](tasks/quadarm_prep.md), [camera plates](tasks/cameraplates.md) | - | 60 |
| [receiver mount](tasks/receiver_mount.md) | [airframe](parts/airframe.md), [receiver](parts/receiver.md), [tape & velcro tape](parts/tapeetc.md) | [receiver bind](tasks/receiver_bind.md) | - | 30 |
| [power loom nodes](tasks/nodes.md) | [wire](parts/wire.md), [heat shrink](parts/tapeetc.md), [PM02 incl with flight controller](parts/flightcontroller.md) | [XT to wires](tasks/xtwires.md) | wire prep, solder, heat shrink | 120 |
| [radio wires](tasks/radio_wires.md) | [radio](parts/radio.md) | [BEC prep](tasks/bec_prep.md) | - | 10 |
| [tail setup](tasks/tail_setup.md) | [airframe](parts/airframe.md), [radio antenna](parts/radioantenna.md), [glue & tape](parts/tapeetc.md), [servo lead extensions](parts/servoext.md) | [servo setup](tasks/servo_setup.md) | gluing | 60\*\* |
| [wing setup](tasks/wing_setup.md) | [airframe](parts/airframe.md), [glue & tape](parts/tapeetc.md), [servo lead extensions](parts/servoext.md) | [servo setup](tasks/servo_setup.md), [GPS mount](tasks/gps_mount.md) | gluing | 45\*\* |
| [frame brackets](tasks/frame_brackets.md) | [flight controller](parts/flightcontroller.md), [screws](parts/screwsetc.md) | [bracket prep](tasks/bracket_prep.md), [wood frame](tasks/wood_frame.md) | - | 20 |
|  |  |  |  |  |

\*The estimated times might be way off.  
\*\*Does not take into account time required for glue to dry, during the task.

## Round Three
These tasks requires at least one "Round Two" task to be done first.

| Task | Parts reqd | Preceding Tasks | Involves | Est time |
| -- | -- | -- | -- | --: |
| [quadarm assemble](tasks/quadarm_assemble.md) | [heat shrink](parts/tapeetc.md). [screws](parts/screwsetc.md) | [quadarm prep](tasks/quadarm_prep.md), [quad ESC solder](tasks/quadesc_solder.md) | heat shrink | 30 |
| [battery velcro](tasks/battery_velcro.md) | battery, airframe, velcro straps, velcro tape | [receiver mount](tasks/receiver_mount.md) | - | 20 |
| [tail glue](tasks/tail_glue.md) | [airframe](parts/airframe.md), [glue](parts/tapeetc.md) | [tail setup](tasks/tail_setup.md) | gluing | 30 |
|  |  |  |  |  |

## Round Four+
Remaining tasks and rounds.

| Round | Task | Parts reqd | Preceding Tasks | Involves | Est time |
| -- | -- | -- | -- | -- | --: |
| 4 | [Airframe Close](tasks/airframe_close.md) |  |  |  |  |
| 5 | [finish build](tasks/finish_build.md) |  |  |  |  |
|  |  |  |  |  |  |
