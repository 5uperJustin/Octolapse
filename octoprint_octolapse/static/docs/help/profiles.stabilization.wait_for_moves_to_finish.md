Normally, Octolapse sends an M400 command before taking a snapshot in order to stabilize the snapshot.  This flushes the gcode buffer, and introduces a slight pause in the print.  However, this is absolutely necessary to get a perfectly smooth timelapse.  Disabling this option prevents a pause caused by the M400 command, but will result in a jerky timelapse, similar to the stock timelapse plugin.  Additionally, Octolapse will not retract, lift, or travel when this option is disabled.

*Note*: Disabling **Wait For Moves To Finish** is not the same as disabling stabilization on each axis.