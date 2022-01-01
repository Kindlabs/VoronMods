# Kind Labs's Klicky Mod

(images/front.png)

## Voron V2 Clockwork 2 Direct Mount MGN12 X Carriage

This is a modified Clockwork 2 X carriage for the Voron 2.4 which directly interfaces
with the Klicky. This is based on [BluedragonX's Klicky Carriage][1] which is based on [Arkeet's MGN12 carriage][2].

The primary benefits of this approach are more rigid mounting of probe and
reduced offset from the nozzle. Hotend airflow may also be improved as the rear
of the carriage is now open.

This mod does not work with the standard fixed dock mounts as the location of
the probe is changed in relation to the hotend. I have included new fixed mount
to account for this.

### Installation

You will need to print each of the following:

- KlickyCW2_x_carriage_frame_left.stl
- KlickyCW2_x_carriage_frame_right.stl

And one of the two dock mounts from BluedragonX's Klicky Carriage:

- v2.4_x_carriage_dock_mount_fixed.stl
- v2.4_x_carriage_dock_side_mount_fixed.stl

Bolt together the two halfs of the carriage as normal. Follow the instructions
for the regular Klicky AB mount to install the magnets and wiring.

### Setup

This mod changes the standard Klicky probe offset so you will need to adjust your settings to account for this.

The only value you should need to adjust is the y_offset for the probe. The new value is 17.5mm.

Both dock mounts are 4mm shorter in the Z direction. The fixed dock mount is also 2mm longer in the Y direction.


[1]: https://github.com/jlas1/Klicky-Probe/tree/main/Usermods/bluedragonx "BluedragonX's Klicky Carriage"
[2]: https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/arkeet/mgn12 "Arkeet's MGN12 Carriage"
