# asmctl
Apple System Management Controller

Asmctl is a command line tool for Apple System Management Controller,
which controls keyboard backlight and LCD backlight.

Asmctl uses sysctl variables of dev.asmc.0.* and hw.acpi.video.lcd0.*
which are provided by FreeBSD kernel.
